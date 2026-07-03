# heirloom-citations-darwin

Canonical reference documentation for the Heirloom Darwin port.
A collection of primary sources — Bell Labs CSTRs, BSTJ papers,
early Unix books, and oral-history material — that the sibling
`heirloom-*-darwin` code repos cite by name in their
`BIBLIOGRAPHY.md`.

> **Not authoritative.** All content in this repo is preserved
> upstream at the TUHS Unix Heritage Archive
> (<https://www.tuhs.org/Archive/>).  This repo is a curated subset
> for offline / mirrored / self-contained deployment of the Heirloom
> Darwin port.

## What's in this repo

```
tech-reports/
  bell-labs-cstr/    Bell Labs Computing Science Technical Reports (64 PDFs)
                     e.g. #54 Ossanna troff, #114 grap, #116 pic
  usg-library/       AT&T USG Library index (INDEX only; content ~600 MB)

papers/
  bstj-1978/         Bell System Technical Journal 57(6.2), July-August 1978
                     — the iconic Unix special issue (~8 selected papers)

books/
  Draft-KandR-C-Book1977.pdf
                     Kernighan & Ritchie's 1977 pre-publication draft of
                     'The C Programming Language', rediscovered by Tom
                     Lyon in December 2022.

oral-history/        Pointers to TUHS oral history collection.
```

Total repo size: ≈ 105 MB (CSTRs + K&R draft + BSTJ selection).

The USG Library (~600 MB, 187 PDFs), the full BSTJ 1978 issue (~200 MB, 22
papers), and the oral history transcripts are NOT bundled here.  They
are indexed with pointers to the TUHS Archive; fetch them under your own
licence reading.

## Which sibling repos cite this

Each Heirloom Darwin code repo cites specific documents from this
collection in its `BIBLIOGRAPHY.md`:

| Repo                              | Cites (examples)                              |
| :-------------------------------- | :-------------------------------------------- |
| `heirloom-sh-darwin`              | Bourne 1978 (BSTJ p.1931)                     |
| `heirloom-devtools-darwin`        | Feldman 1979 (make), Johnson 1975 (yacc)      |
| `heirloom-toolchest-darwin`       | Aho/Weinberger/Kernighan 1988 (awk)           |
| `heirloom-doctools-darwin`        | Ossanna 1977 (CSTR #54), Lesk 1976 (tbl)      |
| `heirloom-pkgtools-darwin`        | Sun 1992 (Application Packaging Guide)        |
| `heirloom-workspace-darwin`       | CWE Top 25, OWASP Top 10, ATT&CK              |

## Licence

Every PDF preserved here is © its original publisher (Bell Labs, AT&T,
Berkeley, Prentice-Hall, Sun Microsystems).  We claim no rights over
the primary content.

The **index files** and this **README** are CC-BY-4.0, © 2026 moonman81.

## Provenance

The material was harvested from the **reduxed-sunsite mirror** at
`/Volumes/mirrors-reduxed/sunsite.icm.edu.pl` on 2026-07-03.  That
mirror is itself a downstream copy of the TUHS Unix Heritage Archive.

## See also

- `PROVENANCE.md`   — chain of custody
- `BIBLIOGRAPHY.md` — reference list (recursive — this repo is itself
                     a bibliography of primary sources)
- `INDEX.md`        — full itemised listing of every PDF here + pointer
                     to upstream

- <https://www.tuhs.org/Archive/> — canonical upstream
- <https://github.com/moonman81/heirloom-workspace-darwin> — hub

## Related repos

- <https://github.com/moonman81/heirloom-sh-darwin>
- <https://github.com/moonman81/heirloom-devtools-darwin>
- <https://github.com/moonman81/heirloom-toolchest-darwin>
- <https://github.com/moonman81/heirloom-doctools-darwin>
- <https://github.com/moonman81/heirloom-pkgtools-darwin>
- <https://github.com/moonman81/heirloom-workspace-darwin>
- <https://github.com/moonman81/heirloom-vi-darwin>
- <https://github.com/moonman81/heirloom-ancestors-darwin>
