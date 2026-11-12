---
date: 2026-11-11
type: policy
project: website
approved_by: mugiwarafx
---

# Direct proposal intake

Adopted for the direct-submission form. This replaces the email-draft
transport described in [2026-004](2026-004-proposal-review-and-commitments.md)
when that form is used. The review process and explicit commitment rules
in that decision continue to apply.

The form records received proposals as issues in the private
`accesslibre/intake` repository. Required fields are the accessibility
barrier and a reply email. Affected users and name or organization are
optional. Credentials remain on the server.

The service checks spam protection and the repository's private
visibility before creating a record. The requester receives a reference
only after the record has been saved. That confirmation acknowledges
receipt; it does not mean the project has been accepted.

Repeating the same submission ID returns its recorded reference for
30 days. Delivery metadata contains a payload hash, reference and state,
not the proposal text. The metadata expires after 30 days. Proposal text
remains in the private intake record for review.

If delivery cannot be confirmed, the form preserves the text and directs
the requester to contact the coordinator with the reference before
another submission. It does not automatically repeat uncertain writes.

The form's promise to ask before publishing proposal content remains in
force. Private intake records and correspondence are separate from public
project decisions. This change does not introduce a publication policy
or an additional email or Discord notification service.
