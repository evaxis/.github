# Initial organisation foundations contract

## Contract status

Closed for initial file preparation: local governance, links, workflow syntax
and credential-pattern validation passed. Publication and security-setting
verification remain bootstrap operations reported separately. This historical
contract does not authorise future product implementation.

## Goal and approved scope

Bootstrap only `evaxis/.github`, `evaxis/evaxis` and `evaxis/architecture`:
cARL from the first commit, factual documentation, shared community governance,
canonical avatar references and non-destructive GitHub security settings.
Tier 1 scoped file writes and Tier 2 governance/API writes are approved within
that boundary. No harness authority changes are approved.

## Plan and expected files

1. Inspect existing state and the stable cARL contract.
2. Initialise cARL, select the foundations profile, populate repository memory.
3. Add `profile/README.md`, root community health files, `THIRD_PARTY_NOTICES.md`,
   `.github/CODEOWNERS`, issue/PR templates and a read-only governance workflow.
4. Validate locally, create the initial commit, push once to empty `main`.
5. Apply available protections, then verify actual GitHub state.

## Non-goals and forbidden scope

No product implementation, fictional schemas/findings/tests, licence selection,
cloud or language choice, services, paid resources, releases, ownership/member
changes, unrelated project changes, replacement artwork or fabricated HTML.
No force pushes, resource deletion, bypassed reviews, auto-merge, weakened rules,
workflow administration tokens or secrets.

## Architectural and security constraints

Preserve all invariants and boundaries in `memory.md` and the bundled policy.
Keep canonical cARL assets intact; repository-specific policy belongs in memory.
Use the API-provided avatar URL. Public visibility grants no new licence.

## Contract assertions and validation

1. All three public repos contain cARL in their root commit: inspect remote
   history and recursive Git trees.
2. Only core governance and CI/CD packs are effective: run `carl doctor`,
   `status`, `pack effective`, `trace`, `harness status`.
3. Branding links resolve and plans are not presented as implementations:
   check local Markdown targets, remote URLs, avatar and documentation.
4. Governance controls are real: read back settings, required checks and
   protection rules; report unsupported or blocked settings honestly.
5. No secrets or implementation introduced: inspect staged content, run
   credential-pattern checks and `git diff --cached --check`; run real cARL CI.

## Risks, stop conditions and escalation

Stop an operation on permission/policy failure or unexpected existing content.
Never weaken settings to retry. Escalate reserved decisions and sole-maintainer
lockout risks. No independent reviewer exists yet: require PRs without an
impossible self-approval requirement; do not grant an automation bypass.

## Carry-forward and context reset

Only invariants and stable memory carry forward. Subsequent content changes use
feature branches and PRs. Close this bootstrap contract after preparation and
local validation; create a new scoped contract for each later change.
