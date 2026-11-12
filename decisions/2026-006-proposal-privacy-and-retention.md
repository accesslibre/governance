---
date: 2026-11-11
type: policy
project: website
approved_by: mugiwarafx
---

# Proposal privacy and retention

Applies to LibreAccessibility proposals received through the form, email
or Discord. It supersedes earlier IATF wording that allowed publication
by default or indefinite private retention. The receipt mechanism in
[2026-005](2026-005-direct-proposal-intake.md) is unchanged.

## Private originals and public summaries

LibreAccessibility uses proposals and reply details to review accessibility
barriers, contact requesters and coordinate agreed work. Proposals are not
used for marketing. Originals stay in the private `accesslibre/intake`
repository, accessible only to authorized reviewers. Cloudflare handles
form delivery and spam checks; GitHub stores the intake records.

Public request records are rewritten summaries of the barrier, outcome
and reasons, never form transcripts. Remove unnecessary contact details,
medical information and context that could identify a person. Removing
names alone does not guarantee anonymity.

Before publishing a proposal summary, show the requester the exact text
and obtain affirmative permission. Keep the approval privately with the
approved version. Silence is not permission; material changes need a new
approval. Declining publication does not affect review of the proposal.

Record relevant Discord decisions without copying conversations or
disclosing private proposal details. Do not treat a public Discord message
as permission to republish a proposal summary. Private messages belong
in private channels, not public project discussions.

## Retention and review

1. Keep only the original information needed while reviewing or helping
   with a proposal. Review active records at least annually.
2. When a proposal is closed, including one explicitly closed as abandoned,
   record a review date 12 calendar months after closure. At that review,
   delete or genuinely anonymize personal data that no longer has a
   justified purpose. Remove unnecessary data sooner when appropriate.
3. For ongoing projects, retain necessary contacts, agreements and
   permissions while they remain useful. Acceptance does not justify
   keeping the entire original form indefinitely.
4. Keep relevant evidence longer where a legal obligation or the
   establishment, exercise or defence of legal claims justifies it.
   Document the reason, necessary records, restricted access and next
   review date, taking applicable legal and limitation periods into
   account. A claim need not already have been filed. This is not a
   blanket exception for all submissions.

The 12-month review is LibreAccessibility's operating choice, not a
universal GDPR retention period. These rules reflect storage limitation
and the legal-claims exception: [GDPR articles 5.1.e and 17.3.e](https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng)
and the [DPC's retention guidance](https://www.dataprotection.ie/en/faqs/responsibilities-data-controllers/how-long-should-personal-data-be-held-meet-obligations-imposed-gdpr).

## Responsibility and removal

The proposal coordinator maintains the private review register, checks
due reviews monthly and records each outcome. For now this is mugiwarafx,
under [2026-003](2026-003-project-stewardship-and-iatf-transition.md).
Reviews and removal are manual; no automatic proposal deletion is enabled.
Closing an issue does not delete its contents. Removal must consider edit
history, attachments and any organization-controlled copies, including
notifications or exports. Keep only a minimal private record of the review.

The delivery service separately removes receipt metadata after 30 days;
this does not remove proposal text from GitHub.

For access, correction, deletion or withdrawal of publication permission,
write to <contact@libreaccessibility.org>. Assess requests promptly and
explain any justified retention exception. Publication permission is
separate from the legal basis for handling private proposals.

For public summaries, use search-index exclusion where technically
available; it is not an access control and cannot be guaranteed on GitHub.
LibreAccessibility can amend or remove records it controls, but cannot
guarantee removal of third-party forks, caches, screenshots or notifications.
