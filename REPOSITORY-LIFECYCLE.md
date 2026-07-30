# Repository Lifecycle

## Statuses

### Active
The repository is under active development or maintenance.

**Requirements:**
- README with clear purpose, status, and usage instructions
- LICENSE file matching the asset type
- `.gitignore` configured for the project type
- Community files (CONTRIBUTING, CODE_OF_CONDUCT, SECURITY)
- Learning Metadata section (for educational repos)
- Cross-linking to related repositories and the Learning Catalog (for educational repos)

### Deprecated
The repository is no longer actively developed but remains usable.

**Requirements:**
- All Active requirements
- Clear "DEPRECATED" notice at the top of README
- Explanation of why it's deprecated
- Recommendation for alternative (if any)

### Archived
The repository is read-only on GitHub.

**Requirements:**
- GitHub archive setting enabled
- "ARCHIVED" banner at the top of README
- Redirect notice to superseding repository (if applicable)
- Preserved git history
- Description updated to `[ARCHIVED] ...`

---

## Archive Procedure

1. Create a feature branch with the archive notice in README.
2. Submit a PR and merge to main.
3. Archive the repository on GitHub via Settings or API.
4. Update the repository description to include `[ARCHIVED]`.
5. If a superseding repository exists, add a redirect notice.

**Never delete a repository.** Archiving preserves history, issues, and forks.

---

## Deprecation vs Archival

| | Deprecated | Archived |
|---|---|---|
| **Code accessible** | Yes | Yes |
| **Issues/PRs** | Open | Closed |
| **Development** | None expected | None allowed |
| **GitHub badge** | None | "Archived" |
| **When to use** | Still functional but unmaintained | Superseded or obsolete |
