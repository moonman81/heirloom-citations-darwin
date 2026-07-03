# HOWTO — heirloom-citations-darwin

## What to use this repo for

- **Offline research** on the historical Unix corpus without needing
  network access to TUHS.
- **Cross-referencing** the citations that the sibling `heirloom-*-darwin`
  code repos make in their `BIBLIOGRAPHY.md`.
- **Verification** that a Heirloom-Darwin port's design decisions can
  be traced back to specific primary sources.

## What NOT to use this repo for

- Scholarly citation without cross-checking against upstream TUHS or
  the primary Bell Labs / AT&T catalogues.
- Redistribution — the primary content is not moonman81's to license.
- As a replacement for TUHS.  TUHS is authoritative; this is a
  curated subset.

## Reading the collection

```sh
# open a specific CSTR
open tech-reports/bell-labs-cstr/54.pdf
# or from CLI:
qlmanage -p tech-reports/bell-labs-cstr/54.pdf 2>/dev/null &

# open the K&R 1977 draft
open books/Draft-KandR-C-Book1977.pdf

# check which sibling repos cite what
cd ../workspace
grep -r 'Ossanna 1977\|CSTR' */BIBLIOGRAPHY.md
```

## Adding a new citation

If you patch a Heirloom-Darwin code repo and the fix references a
primary source not yet in this collection:

1. Locate the source in the TUHS Archive.
2. Copy the PDF into the appropriate subdirectory of this repo.
3. Update `INDEX.md` with the new entry.
4. Update the citing code repo's `BIBLIOGRAPHY.md` with a pointer
   to the new local path (e.g., `heirloom-citations-darwin:tech-reports/bell-labs-cstr/NN.pdf`).
5. Commit both changes.

Do NOT add a PDF you are not confident is properly licensed for
redistribution as a mirror of TUHS.
