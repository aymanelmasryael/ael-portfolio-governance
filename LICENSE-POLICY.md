# License Policy

## Classification by Asset Type

| Category | License | Examples |
|----------|---------|----------|
| Developer Tools | MIT | Code analyzers, CLIs, utilities |
| Frameworks | MIT | Design systems, component libraries |
| Engines | MIT | Color engines, particle engines, rendering engines |
| UI Components | MIT | Chat interfaces, dashboards, interactive UIs |
| WebGPU / GPU | MIT | Particle systems, 3D engines |
| Design Systems | MIT | Component libraries, design tokens |
| Educational Content | MIT | Courses, academies, references, knowledge bases |
| Prompt Libraries | All Rights Reserved | Prompt collections, prompt IP systems |
| Commercial Visual Assets | Custom Digital License | 3D backgrounds, visual products, brand assets |
| Personal Websites | All Rights Reserved | Personal portfolios, identity pages |
| Legacy Repositories | Archive with inherited license | Superseded or renamed projects |

---

## Decision Matrix

```
Is it software?
├── Yes → MIT
└── No
    └── Is it educational content?
        ├── Yes → MIT
        └── No
            └── Is it a prompt library or prompt IP?
                ├── Yes → All Rights Reserved
                └── No
                    └── Is it a commercial visual asset?
                        ├── Yes → Custom Digital License
                        └── No → All Rights Reserved
```

---

## License File Requirements

- Every repository MUST have a LICENSE file at the root.
- MIT license files use copyright: `Copyright (c) 2026 AEL Digital Studio`.
- Custom licenses are written in full, not referenced by name only.
- Archived repositories retain their original license.

---

## Copyright Line

Standard copyright format for README and HTML footers:

For MIT repositories:
```
**License:** MIT — Free for personal and commercial use.
```

For All Rights Reserved repositories:
```
**License:** © 2026 AEL Digital Studio. All rights reserved.
```

For Custom Digital License:
```
**License:** Ayman Elmasry Digital License — Licensed for personal and commercial use with attribution. Unauthorized redistribution is prohibited.
```
