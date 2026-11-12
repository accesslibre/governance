---
date: 2026-11-11
type: policy
project: null
---

# Repository names for LibreAccessibility

Approved by the organization owner. This decision supersedes the naming
rules in [2026-001](2026-001-repository-naming-policy.md), which remains
available as a historical record.

## Rules

- Use descriptive lowercase names with hyphens, without an organization
  prefix or sequence number.
- Shared services are `website`, `governance`, and `intake`.
- `intake` remains private. Public summaries belong in
  `governance/requests/YYYY-NNN-<slug>.md` after review.
- Historical IATF projects keep `iatf` in their names. `iatf-selfie` and
  `iatf-bot` remain public and archived using GitHub's Archived state.
- Decision numbers stay in `governance/decisions/YYYY-NNN-<slug>.md`.

## Applied names

All repositories are owned by `accesslibre`.

| Previous name | Current name |
| --- | --- |
| `iatf-website` | `website` |
| `iatf-governance` | `governance` |
| `iatf-intake` | `intake` |
| `archived-iatf-selfie` | `iatf-selfie` |
| `archived-iatf-bot` | `iatf-bot` |

The repository IDs, history, visibility, and archival states were
preserved. `.github`, `coga-user-testing-pilot`, and `robodk-voiceaccess`
keep their names.
