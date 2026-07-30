# AEL Portfolio Governance

## Core Principles

1. **License follows asset type** — not repository name or personal preference.
2. **Every repository has a clear lifecycle status** — Active, Deprecated, or Archived.
3. **Governance changes go through PRs** — no direct pushes to governance or portfolio repos.
4. **Consistency over perfection** — apply the standard; improve it later.
5. **Preserve history** — never delete repositories; archive them with redirects.

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

## Governance Process

1. **Propose** — Open an issue or PR against this repository.
2. **Review** — Changes are discussed and refined.
3. **Merge** — Approved changes are merged and versioned.
4. **Apply** — The updated governance is applied to portfolio repositories.

All governance changes follow the same PR workflow as code changes.

---

## Versioning

Governance versions follow semantic versioning:

- **Major**: Breaking changes to policies or structure.
- **Minor**: Additions to policies, new templates.
- **Patch**: Clarifications, fixes, non-substantive updates.
