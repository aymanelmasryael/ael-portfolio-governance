# AEL Portfolio Governance

## Core Principles

1. **License follows asset type** — not repository name or personal preference.
2. **Every repository has a clear lifecycle status** — Active, Deprecated, or Archived.
3. **Governance changes go through PRs** — no direct pushes to governance or portfolio repos.
4. **Consistency over perfection** — apply the standard; improve it later.
5. **Preserve history** — never delete repositories; archive them with redirects.
6. **Governance evolves by explicit decisions, not by accumulated exceptions** — when exceptions outnumber instances of a rule, change the rule, not the policy silently.
7. **Policies before implementations** — a change is documented in governance before it is propagated to repositories.
8. **Canonical source over duplicated rules** — each policy exists in exactly one place; other files reference it, never redefine it.
9. **Archive instead of delete** — git history is preserved, no repository is ever destroyed.
10. **Consistency over convenience** — applying the standard is preferred over a fast workaround.

---

## The Four Portfolio Layers

```
AEL Portfolio
│
├── 1. Engineering Portfolio
│   Developer tools, engines, frameworks, design systems
│   License: MIT
│
├── 2. Learning Portfolio
│   Courses, academies, references, educational resources
│   License: MIT
│
├── 3. Commercial IP
│   Prompt libraries, brand assets, visual products
│   License: All Rights Reserved or Custom
│
└── 4. Legacy Layer
│   Archived repositories with preserved history and redirects
│   License: As inherited from original status
```

---

## Repository Lifecycle

```
┌─────────┐     ┌────────────┐     ┌──────────┐
│  Active  │ ──→ │ Deprecated │ ──→ │ Archived  │
└─────────┘     └────────────┘     └──────────┘
```

- **Active**: Under active development or maintenance.
- **Deprecated**: No longer actively developed but still usable. README notes the status.
- **Archived**: Read-only on GitHub. README includes redirect notice to superseding project (if any).

---

## Governance Lifecycle

Governance itself has a lifecycle. Every change to this repository follows these stages:

```
┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────────┐    ┌─────────┐    ┌───────────────┐
│ Proposal  │ →  │  Review  │ →  │ Decision │ →  │ Implement.   │ →  │ Adoption│ →  │ Periodic Rev. │
└──────────┘    └──────────┘    └──────────┘    └──────────────┘    └─────────┘    └───────────────┘
        ↑                                                                                  │
        └────────────────────────────────── Feedback ──────────────────────────────────────┘
```

### Stage Descriptions

| Stage | What happens |
|-------|-------------|
| **Proposal** | An issue or PR is opened with the proposed change, rationale, and expected impact. |
| **Review** | The change is evaluated for consistency with existing policies and core principles. |
| **Decision** | The change is accepted, rejected, or sent back for revision. Decisions are documented with reasoning. |
| **Implementation** | Documentation, templates, and affected files are updated. |
| **Adoption** | The policy is applied gradually to portfolio repositories. Older repos may get a migration window. |
| **Periodic Review** | After a set period (typically 3–6 months), the impact of the change is evaluated. |

---

## Governance Change Criteria

A governance change is warranted when one or more of these conditions are met:

- A new situation arises that existing policies do not cover.
- Two or more policies contradict each other.
- A policy has become impractical to implement or enforce.
- The change would affect more than one repository.
- The change reduces complexity or improves clarity without breaking existing rules.

Proposals that affect a single repository only (e.g., a repo-specific README fix) do not require a governance change — they are handled by the repository's own maintenance.

---

## Governance Versioning

Governance versions follow semantic versioning applied to governance itself:

| Level | Scope | Examples |
|-------|-------|----------|
| **Patch (v1.0.x)** | Fixes and clarifications | Typo corrections, wording improvements, adding examples. No policy change. |
| **Minor (v1.x)** | Additions and improvements | New policy, new template, expanded decision matrix. Compatible with existing repositories. |
| **Major (v2.0)** | Breaking changes | Change to licensing philosophy, redefining the lifecycle, restructuring the portfolio layers. Requires a migration plan. |

---

## Governance Process

1. **Propose** — Open an issue or PR against this repository.
2. **Review** — Changes are discussed and refined.
3. **Merge** — Approved changes are merged and versioned.
4. **Apply** — The updated governance is applied to portfolio repositories.

All governance changes follow the same PR workflow as code changes.
