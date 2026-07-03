# PROVENANCE — heirloom-citations-darwin

## Chain of custody for the reference-documentation collection

```
┌─────────────────────────────────────────────────────┐
│  Bell Labs, USG, Berkeley, university publishers    │  1969-1988
│  (original authorship + publication)                │
└──────────────────┬──────────────────────────────────┘
                   │  Bit Savers / TUHS chain
                   │  (community preservation)
                   ▼
┌─────────────────────────────────────────────────────┐  ~2000-present
│  TUHS Unix Heritage Archive                         │  https://www.tuhs.org/
│  https://www.tuhs.org/Archive/                       │
└──────────────────┬──────────────────────────────────┘
                   │  Mirror
                   ▼
┌─────────────────────────────────────────────────────┐  present
│  ICM Warsaw (sunsite.icm.edu.pl)                    │  Public HTTP mirror
└──────────────────┬──────────────────────────────────┘
                   │  local reduxed-sunsite substrate
                   │  Curation + N3 ontology by another agent
                   │  (2026-06 → 2026-07)
                   ▼
┌─────────────────────────────────────────────────────┐  2026-07-03
│  moonman81 / heirloom-citations-darwin              │  THIS repo — curated
│                                                     │  subset for Heirloom
│                                                     │  Darwin port citations
└─────────────────────────────────────────────────────┘
```

## Verifiable trail

- Every PDF committed to this repo has SHA-256 recorded in
  `MANIFEST.sha256` (regenerable via `sha256sum tech-reports/... > MANIFEST.sha256`).
- Every PDF is also present in the upstream TUHS Archive at the same
  filename; cross-check bit-exactness by fetching from TUHS.
- No PDF in this repo has been edited by moonman81.

## Governance

- No CLA. See `CONTRIBUTING.md`.
- No CI budget. Pre-commit runs locally.
- Take-down requests honoured without argument via
  `.github/ISSUE_TEMPLATE/attribution_concern.md`.

## Related repos

- `moonman81/heirloom-sh-darwin` .. `heirloom-workspace-darwin` — code repos.
- `moonman81/heirloom-vi-darwin` — patches-only vi scaffold.
- `moonman81/heirloom-ancestors-darwin` — museum-tier ancestor sources.
