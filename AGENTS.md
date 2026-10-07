# AGENTS.md

## Project identity

PROJECT: Kirion-Lucien public profile
REPOSITORY: Kirion-Lucien/Kirion-Lucien
TECHNICAL AUTHORITY: Kirch Ivan Balite
FORGE NEST LEVEL: NEST-0 — Bootstrapped

## Purpose

This repository is the public GitHub profile and showcase surface for **Lucien Marek Sol**, the Kirion Smithy interface specialist.

It exists to present Lucien's public identity, UI/UX and frontend specialization, selected public-facing work, and validated profile assets.

It does **not** serve as the source of truth for private Kirion orchestration, connector mechanics, prompts, internal routing, private repositories, or private Forge procedures.

## Current authority

DEFAULT BRANCH: main
CURRENT ACCEPTED BRANCH: main
CURRENT ACCEPTED SHA: aec42f5a413e5041c0fae13b73b4d7a85014c398
CURRENT PHASE: Profile rework planning after Forge bootstrap

## Architecture invariants

- The profile must remain a GitHub-native showcase, not a simulated application UI.
- Lucien's primary public specialization is UI/UX systems and frontend engineering.
- Public content must not expose internal connector mechanics, prompts, private routing, or private repository names.
- Claims presented as existing work must be supported by real public repository state.
- Future or planned work must be clearly labeled as such.
- Repository-local images referenced by README.md must exist, decode successfully, and render through GitHub.
- Important information must not depend on tiny text baked into raster images.
- Responsive readability and narrow GitHub rendering are acceptance concerns, not optional polish.
- Visual design should demonstrate hierarchy, restraint, accessibility, and interface judgment rather than merely claim them.

## Repository boundaries

- `README.md` — public profile content and information architecture.
- `assets/` — profile artwork and visual assets used by the README.
- `.forge/` — minimal repository-specific Forge authority and nest records.
- `AGENTS.md` — repository operating boundary for bounded writers.

Writers may modify only surfaces explicitly granted by a Maintainer handoff.

## Security boundaries

- No credentials, tokens, secrets, private prompts, or private infrastructure details may be committed.
- Do not publish private repository names or non-public internal operating details.
- Do not add external scripts or dynamic content that creates an unnecessary tracking or supply-chain dependency for the profile.

## Validation expectations

For profile candidate work, validation must include:

1. exact source and candidate SHA verification;
2. diff-scope review;
3. README path/link inspection;
4. repository-local image existence and decode verification;
5. GitHub-render compatibility review;
6. desktop and narrow/mobile readability review where render evidence is available;
7. confirmation that public claims match observable repository state;
8. confirmation that no broken assets, generated gibberish, or unreadably small image text remain.

There is no application build or runtime test suite in this repository unless one is added under explicit authority.

## Git policy

- exact starting SHA required for bounded writer work;
- candidate branches are required for implementation changes;
- no direct writer mutation of `main`;
- no force push by default;
- no silent history rewriting;
- preserve unrelated work;
- writers do not self-accept, self-integrate, or self-promote.

## Forge memory

SSOT: not installed at NEST-0
AUTHORITY: .forge/AUTHORITY.md
ARCHITECTURE: not installed at NEST-0
DECISIONS: not installed at NEST-0
ENGINEERING LOG: not installed at NEST-0
HANDOFFS: issued by Maintainer outside this minimal public nest unless later authorized
EVIDENCE: candidate reports and exact Git state

## Prohibited behavior

Without explicit Maintainer authority, do not:

- mutate `main` directly;
- expand this profile repository into unrelated application code;
- present planned repositories or capabilities as already delivered;
- expose internal Kirion/connector implementation details;
- replace validated local assets with unverified generated files;
- add badge walls, fake dashboards, or dense decorative UI that undermines the profile's own UI/UX standard;
- weaken or bypass stated validation merely to finish faster.
