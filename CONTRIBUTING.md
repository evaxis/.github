# Contributing to Evaxis

Evaxis is in the foundation/design stage. Contributions currently focus on
documentation, architectural questions and explicit contract proposals.
No implementation language, backend, cloud or Evaxis licence has been selected.
Public visibility does not grant an open-source licence. Contribution-rights
terms are undecided: discuss substantial contributions before submitting them.

## Workflow

1. Read the affected repository's README, cARL loader and canonical
   `.github/carl/` memory, invariants, trust boundaries and current contract.
   Shared community defaults do not replace repository-local cARL.
2. Discuss the intended outcome in an issue without sensitive data. Clearly
   label statements **Confirmed**, **Proposed** or **Undecided**.
3. Use a feature branch or fork. Define a scoped
   `.github/carl/current-pr-contract.md` before implementation, based on the
   bundled template. Include non-goals, expected files, 3-5 acceptance assertions,
   validation, stop conditions and escalation triggers.
4. Make small, reviewable changes. Preserve independence and all cARL invariants.
   Do not add product code, schemas, fabricated findings, dependencies, cloud
   infrastructure or licensing terms without explicit approval.
5. Run the pinned cARL CLI: `carl doctor`, `carl status`, `carl pack effective`,
   `carl trace`, `carl harness status`; check Markdown links and `git diff --check`.
   Governance CI is not evidence that a native agent obeyed its instructions.
6. Reconcile durable memory and relevant architecture docs, then close or
   supersede the contract. Open a PR describing validation and limitations.
   Obtain maintainer review; never bypass protections or enable auto-merge.

Managed cARL files and generated adapters must remain canonical. Put Evaxis
decisions and repository-specific invariants/boundaries in `memory.md`, rather
than hand-editing generated loaders or silently accepting runtime drift.
Use documented cARL selection/profile commands. Keep
`.github/carl/**` excluded from JFrog Boost optimisation if Boost is used.

No product build or test runner exists yet. Do not select one merely to satisfy
a check. Planned schemas and conformance fixtures require specification first.

Read the [code of conduct](https://github.com/evaxis/.github/blob/main/CODE_OF_CONDUCT.md)
and [security policy](https://github.com/evaxis/.github/blob/main/SECURITY.md).
