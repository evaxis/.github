![Evaxis logo](https://avatars.githubusercontent.com/u/349042465?v=4)

# Evaxis

**Evidence Across Every Axis.**

Evaxis (EVidence + AXIS) is an independent, provider-neutral security evidence,
provenance, historical analysis and assurance platform being designed to connect
security conclusions to their evidence and explain change over time.

## Status

**Confirmed:** foundation/design stage. These repositories contain governance,
architectural documentation and planned contract directories, not an operating
product. Evidence collection, storage, drift processing, hosted services,
authentication and billing are not implemented.

## Architectural principles

- Independent core: no required provider, integration, hosted service or fixed
  execution environment.
- Portable storage, including local and customer-managed options; no backend
  is selected.
- Design for evidence integrity, provenance, collector identity, timestamps,
  completeness, freshness and replay protection.
- Distinguish environmental change from schema, collection, identity-resolution
  and evaluation change.
- Preserve client-side, server-side and hybrid processing choices.
- Useful baseline functionality should not require a paid hosted service;
  entitlements must not be inseparable from a storage provider.

These are design constraints, not claims of implemented security controls.

## Repositories

| Repository | Purpose |
|---|---|
| [Evaxis core](https://github.com/evaxis/evaxis) | Future independent core and planned evidence contracts |
| [Architecture](https://github.com/evaxis/architecture) | Architectural decisions, roadmap and threat-model planning |
| [Organisation foundations](https://github.com/evaxis/.github) | Shared community guidance and cARL-governed identity |

## Relationship with Maester

**Proposed:** Maester integration, including possible Maester Packs and Maester
Cloud Plugins. Evaxis is independent of Maester; Maester is not its execution
or storage foundation. Provider APIs, structured evidence storage, licensing and
revenue sharing are not established product contracts. No partnership,
affiliation or endorsement is claimed.

## Participate safely

Read [contribution guidance](https://github.com/evaxis/.github/blob/main/CONTRIBUTING.md),
[conduct expectations](https://github.com/evaxis/.github/blob/main/CODE_OF_CONDUCT.md)
and [support guidance](https://github.com/evaxis/.github/blob/main/SUPPORT.md).
Report vulnerabilities through the affected repository's
[security policy](https://github.com/evaxis/.github/blob/main/SECURITY.md), not a public issue.

**Undecided:** implementation languages, cloud providers, databases, technical
contracts and commercial licensing. Public repositories are not a declaration
of open-source licensing.
