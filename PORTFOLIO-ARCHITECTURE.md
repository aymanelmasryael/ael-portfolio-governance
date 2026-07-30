# Portfolio Architecture

```
AEL Portfolio
│
├── 1. Engineering Portfolio
│   │  Developer tools, engines, frameworks, design systems
│   │  License: MIT
│   │
│   ├── ael-reference-engine
│   ├── ael-omega-platform (was ael-color-os)
│   ├── ael-omega-particles
│   ├── ael-image-color-extractor
│   ├── ael-particles-lab
│   ├── ael-code-analyzer
│   ├── ael-design-system
│   ├── ael-3d-particle-backgrounds-library (custom license)
│   ├── ael-qa-studio
│   ├── ael-markdown-cms
│   ├── ael-analytics-dashboard
│   └── ael-ai-chat-interface
│
├── 2. Learning Portfolio
│   │  Courses, academies, references, educational resources
│   │  License: MIT
│   │
│   ├── Courses
│   │   ├── ael-engineering-academy
│   │   ├── AEL-Sovereign-CS50x-2026-2027
│   │   ├── ael-learn-opencode-course
│   │   ├── ael-learn-github-course
│   │   ├── cs-academy-v2 (pre-release)
│   │   ├── problem-solving-academy (pre-release)
│   │   └── ai-ux-guide (pre-release)
│   │
│   └── References
│       ├── ael-llm-engineering-reference-2026
│       ├── ael-terminal-engineering-reference-2026
│       └── ael-ai-alignment-quotes
│
├── 3. Commercial IP
│   │  Prompt libraries, brand assets, visual products
│   │  License: All Rights Reserved / Custom
│   │
│   ├── ael-1000-prompts-library
│   └── ael-brand-system
│
├── 4. Legacy (Archived)
│   │  Preserved with history and redirects
│   │
│   ├── ael-color-os → redirected to ael-omega-platform
│   ├── ael-prompt-framework → redirected to ael-1000-prompts-library
│   └── aymanelmasry.me
│
└── Meta
    ├── aymanelmasryael.github.io (personal profile)
    ├── ael-learning-catalog (learning index)
    └── ael-portfolio-governance (this repository)
```

## Layer Relationships

- **Engineering → Learning**: Engineering tools are prerequisites for learning courses.
- **Commercial IP**: Standalone — not referenced by other layers.
- **Legacy**: Archived repos redirect to their active counterparts.
- **Meta**: Governance and catalog repos manage the portfolio itself.

## Cross-Linking Rules

- Every Learning Portfolio repository links to the Learning Catalog.
- Every repository links to repositories that supersede it (if archived).
- Related repositories within the same layer cross-link where relevant.
