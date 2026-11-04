# Domain docs

Use a single-context layout:
- DOMAIN.md at the repository root.
- Relationships, lifecycles, and module responsibilities under docs/domain-model.md.
- Architecture Decision Records (ADRs) under docs/adr/.

Before exploring the codebase or changing domain behavior, read DOMAIN.md, docs/domain-model.md, and relevant ADRs.
If absent, proceed silently.
Create them only when domain terms or decisions are resolved.

Check each document's status. Proposed decisions require owner approval before implementation.
Use docs/first-version.md for scope; a concept in the model does not add a feature to the release.

Use the glossary's terms consistently.
Identify conflicts with existing ADRs explicitly.
