# Documentation notes

## Source of truth

[MoBoOk_Final_Concept.pdf](MoBoOk_Final_Concept.pdf) is the canonical product concept. The Arabic source files are preserved unchanged.

The [site map](MoBoOk_SiteMap.md) and [policies](MoBoOk_Policies.md) are planning drafts. Their presence here does not mean that a service is live, that the policies are legally approved, or that the described controls have been built.

## Items to reconcile before implementation

| Topic | Review needed |
| --- | --- |
| Content and discovery | The site map includes possible video calls, popular voices and follow actions. These do not establish scope beyond the final concept's text/audio experience and rejection of follower-based popularity. |
| Group permissions | The final concept gives members equal powers and requires unanimous approval for adding or removing members. Owner-only group deletion in the site map needs review. |
| Disclosure and consent | A connection requires both people to agree. Each person's disclosures remain independently controlled, voluntary and reversible. No trust level should silently open. |
| Deletion | The final concept leaves deletion behavior open. The policy draft both restricts deletion after approval and describes deletion/retention rights. One consistent rule is still needed. |
| Blocking and reporting | The final concept leaves blocking, unilateral disconnection and access to identity during reports unresolved. Later draft details are proposals, not settled decisions. |
| Authentication and encryption | The policy draft names bcrypt and end-to-end encryption. These are unverified design proposals, not implementation facts. The Firebase authentication, key-management and identity-separation design needs review. |
| Providers and retention | Claims about no third parties need reconciliation with the planned Firebase stack and the draft's Google Analytics and Sentry references. Retention periods also need approval and implementation. |
| Operations and legal terms | Moderation deadlines, age rules, Egyptian governing law and arbitration clauses are unreviewed draft terms. The listed `@mobook.app` addresses are unverified placeholders, not confirmed support channels. |
| Dates and counts | The policy's June 2024 date is retained as supplied, not a launch or approval date. The site map's total screen count is a draft estimate, not a delivery commitment. |

## Current stage

This repository contains a concept, designs and local HTML prototypes. It does not contain the Flutter app, Firebase backend, production authentication or a verified secure messaging implementation.

The previews use local browser storage for demo state. Preview 1 and Preview 2 store the entered demo password in plain text alongside the account email and voice ID. Use a made-up password that is not used anywhere else, and sample content only. This is not production authentication. The HTML designs reference external Google Fonts, so loading those fonts may require an internet connection.
