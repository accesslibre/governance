# Public request summaries

Rewritten summaries of reviewed LibreAccessibility proposals, alongside
earlier IATF records. New publications follow the
[privacy and retention policy](../decisions/2026-006-proposal-privacy-and-retention.md).

## Relationship to `intake`

- **`intake` (private):** raw intake from the website form,
  email, or Discord. May contain personal contact details, sensitive
  context, spam, or harmful content. Only authorized reviewers can read it.
- **`governance/requests/` (public, this folder):** filtered and
  redacted summaries of requests that have been accepted, declined,
  deferred, or reshaped. These are what the public registry and
  transparency page can link to.

A request is **never** published verbatim. Show the requester the exact
summary and obtain affirmative permission before publication, including
for accepted projects. No reply means no publication. Keep approval in
private intake, not in this public folder. Summaries remove personal
contact details, private addresses, and identifying information about
individual users of assistive technologies before publication.

## What gets published

With permission for the exact summary:

- Accepted requests, once the project repository exists.
- Declined or deferred requests, when there is public value in
  recording the reasoning (e.g. recurring out-of-scope themes).
- Requests that were reshaped before acceptance, with a short note on
  what changed.

Spam, hostile messages, and clearly off-topic submissions are filtered
out at the private intake stage and are not summarized here.

## File naming

`YYYY-NNN-<slug>.md`, where `NNN` is a zero-padded sequence number for
that year (e.g. `2026-001-plain-language-reader.md`). Numbering belongs
in governance records, not in repository names — accepted projects use
descriptive names without an organization prefix, under
[the current naming policy](../decisions/2026-002-libreaccessibility-repository-names.md).

## Minimal entry shape

```markdown
---
date: 2026-05-02
status: accepted | declined | deferred | reshaped
project: <project-slug>           # if accepted
---

## Need

Short, plain-language description of the accessibility need.

## Outcome

What LibreAccessibility decided and why.
```

## Editorial policy

Use the current [privacy and retention policy](../decisions/2026-006-proposal-privacy-and-retention.md),
including Discord decisions, indexing limits and removal requests.
Do not store originals, contact details or evidence of permission here.
