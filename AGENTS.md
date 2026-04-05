# AGENTS

## Operating Rules

- Use `arc-ideabrowser-openclaw-flow` when research/extraction from IdeaBrowser is required.
- Use `arc-implementation-plan-progress` when generating or revising implementation plans and progress tracking.
- Keep outputs deterministic and local-first.
- Do not deploy, commit, or push unless explicitly asked.

## Build Preferences

- Prefer Next.js + TypeScript + shadcn/ui.
- Prefer Convex + Clerk + Vercel.
- Prefer ESNext syntax and zsh-compatible commands.
- Use Jest for unit tests and Playwright for e2e.

## Delivery Style

- Ship vertical slices with tests.
- Avoid speculative architecture; implement only scoped requirements.
- Mark unknowns explicitly instead of inventing details.
