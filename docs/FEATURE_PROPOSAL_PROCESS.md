# Feature proposal process

Canonical template: [Feature proposal](../.github/ISSUE_TEMPLATE/feature-proposal.md), version **1.0.0**.

Use discoveryOS information for Proposed outcome through Current behaviour or workaround, linking the source records. Treat the remaining proposal sections as hypotheses informed by evidence. Record unknowns explicitly. The template does not fetch discoveryOS data automatically.

Create proposals in the responsible product repository and add the resulting issue to the relevant GitHub Project. Do not put private customer evidence in this public defaults repository.

## Distribution

This public `.github` repository supplies organisation defaults. Repositories with their own `.github/ISSUE_TEMPLATE` templates or configuration override the entire default template collection; maintain a local copy there through reviewed pull requests. Do not delete their other templates to force inheritance.

## Iteration

Propose template changes through a pull request for process-owner review. Update the version marker and this changelog together. Use patch versions for wording fixes, minor versions for compatible additions and major versions for removed fields or changed meanings. Synchronise local copies through reviewed pull requests after approval. Existing proposals retain their original version; do not silently rewrite them.

The Markdown template is editable and does not enforce mandatory field completion. Review all 15 sections before accepting a proposal.

## Changelog

- **1.0.0:** Initial user-approved feature proposal structure; discoveryOS source prompts, explicit hypotheses and assumptions, target-market clarification and success-measure table.
