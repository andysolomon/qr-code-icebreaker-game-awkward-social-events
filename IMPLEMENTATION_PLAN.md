# IMPLEMENTATION_PLAN

> Linear project: [QR Icebreaker](https://linear.app/arcnology/project/qr-code-icebreaker) (team ARC)
> Semantic release: conventional commits, squash-merge to main, auto-versioning via GitHub Actions

## Phase 1: Foundation (ARC-11 through ARC-16)

- W-000001 (ARC-11): Initialize app shell, routing, CI/CD, and semantic-release.
- W-000002 (ARC-12): Convex backend with core schema (Venue, Session, PromptPack, Prompt, Response).
- W-000003 (ARC-13): Clerk auth for venue owners (patron routes unprotected).
- W-000004 (ARC-14): shadcn/ui setup, layout groups (marketing, dashboard, play).
- W-000005 (ARC-15): Venue CRUD mutations, queries, slug generation.
- W-000006 (ARC-16): Seed 3-5 curated prompt packs, pack selection UI.

## Phase 2: Core Interaction Loop (ARC-17 through ARC-22)

- W-000007 (ARC-17): QR code generation (one per venue, self-serve).
- W-000008 (ARC-18): Anonymous patron session via QR scan (session token in cookie).
- W-000009 (ARC-19): Prompt delivery with time-based rotation.
- W-000010 (ARC-20): Response capture (280 char limit, one per prompt per session).
- W-000011 (ARC-21): Shared prompt board with real-time anonymized responses.
- W-000012 (ARC-22): Mobile UX polish, loading states, error handling.

## Phase 3: Venue Dashboard + Analytics (ARC-23 through ARC-28)

- W-000013 (ARC-23): Venue onboarding wizard (3-step: create, pick pack, get QR).
- W-000014 (ARC-24): Real-time session metrics (active players, today's sessions, response rate).
- W-000015 (ARC-25): Daily/weekly summary views with charts.
- W-000016 (ARC-26): Prompt rotation interval controls + manual advance.
- W-000017 (ARC-27): Venue settings page (name, pack, rotation, pause/active).
- W-000018 (ARC-28): Dashboard home with multi-venue overview cards.

## Phase 4: Subscription + Growth Hooks (ARC-29 through ARC-32)

- W-000019 (ARC-29): Stripe integration, monthly per-venue subscription.
- W-000020 (ARC-30): Subscription gating with 7-day free trial.
- W-000021 (ARC-31): Custom/branded prompt campaigns for subscribers.
- W-000022 (ARC-32): Multi-venue support with per-venue billing.

## Phase 5: Quality + Release (ARC-33 through ARC-37)

- W-000023 (ARC-33): Jest unit tests for Convex functions (80%+ coverage target).
- W-000024 (ARC-34): Playwright E2E for patron play flow.
- W-000025 (ARC-35): Playwright E2E for venue owner dashboard flow.
- W-000026 (ARC-36): Vercel deployment hardening, env separation.
- W-000027 (ARC-37): Smoke test suite and health check endpoint.
