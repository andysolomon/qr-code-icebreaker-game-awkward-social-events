# Contributing

## Branch Naming

```
feat/W-XXXXXX-short-description   # New features
fix/W-XXXXXX-short-description    # Bug fixes
chore/short-description            # Maintenance
ci/short-description               # CI/CD changes
docs/short-description             # Documentation
```

## Commit Messages

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: add QR code generation
fix: resolve session token expiry
docs: update API documentation
chore: update dependencies
```

Commits are validated locally by commitlint via Husky.

## Pull Request Workflow

1. Create a feature branch from `main`
2. Make changes, commit with semantic prefixes
3. Push and open a PR targeting `main`
4. CI must pass (lint, format, build)
5. **Squash & Merge** to main

## Versioning

Releases are automated via [semantic-release](https://github.com/semantic-release/semantic-release):

- `feat:` commits trigger a **minor** version bump (0.1.0 -> 0.2.0)
- `fix:` commits trigger a **patch** version bump (0.1.0 -> 0.1.1)
- `docs:`, `chore:`, `ci:`, `test:` commits do **not** trigger a release

Tags and GitHub Releases are created automatically on merge to main.
