# Decision Matrix

## License Selection

```
START: What type of asset is this?
│
├── Software (tool, engine, framework, library)
│   └── License: MIT
│
├── Educational content (course, academy, reference)
│   └── License: MIT
│
├── Prompt IP (prompt library, prompt system)
│   └── License: All Rights Reserved
│
├── Commercial visual asset (3D backgrounds, visual products)
│   └── License: Ayman Elmasry Digital License
│
├── Personal website / portfolio
│   └── License: All Rights Reserved
│
└── Other
    └── License: All Rights Reserved (default)
```

---

## Active vs Archived

```
START: Is this repository actively developed or maintained?
│
├── Yes → ACTIVE
│   └── Ensure: LICENSE, README, .gitignore, CI
│
└── No
    └── Is it superseded by another repository?
        ├── Yes → ARCHIVE
        │   └── Add redirect notice to superseding repo
        └── No
            └── Is it still functional?
                ├── Yes → DEPRECATE
                │   └── Add deprecation notice to README
                └── No → ARCHIVE
```

---

## New Repository Creation

```
START: Does a repository with similar functionality already exist?
│
├── Yes → Do not create. Archive the duplicate if needed.
│
└── No
    └── Does the name follow the ael- naming convention?
        ├── Yes → Proceed
        └── No → Rename before creation
            └── Apply CHECKLIST.md
```

---

## License Contradiction Resolution

```
START: Does README license match LICENSE file?
│
├── Yes → No action needed
│
└── No
    └── LICENSE file exists?
        ├── Yes → LICENSE is authoritative. Fix README to match.
        └── No → Apply LICENSE-POLICY.md based on asset type.
```

---

## Repository Discovery

```
Question: Are there two repositories with the same codebase?
│
├── Yes → One is the canonical source. Archive the other with redirect.
│
└── No → No action needed
```

```
Question: Does this repository have a clear purpose?
│
├── Yes → Ensure README communicates it in the first paragraph.
│
└── No → Write a purpose statement before any other changes.
```
