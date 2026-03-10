# rfischbackdev Skills Tracker

Owner: `rfischbackdev`  
Last Updated: `2026-03-10`

## What This Tracker Is

This is a lightweight public tracker for the five workflow skills used most often in delivery.  
Weekly updates keep summaries short, practical, and focused on execution value.

## Core Skills

1. `linear`: use the linear skill with Linear MCP to create, update, and track tickets with less context switching.
2. `figma`: use the figma skill with Figma MCP to pull design context and assets for faster implementation.
3. `test-driven-development`: write the failing test first, then minimal code, then refactor safely.
4. `systematic-debugging`: isolate root cause with hypotheses and verification, not random guessing.
5. `verification-before-completion`: run fresh checks before saying work is done. Evidence over assumptions.

## Skill Breakdown

### 1) `linear`

- **Description:** Structured Linear project and issue management using the linear skill.
- **Use cases:** Sprint planning, bug triage, bulk updates, project tracking.
- **Repo / Source:** Local custom skill (no public repo documented).
- **Install / Access:** Use from `~/.codex/skills/linear/`. To get full value, pair it with Linear MCP: `codex mcp add linear --url https://mcp.linear.app/mcp`, enable `rmcp_client`, then `codex mcp login linear`. Restart Codex after login.

### 2) `figma`

- **Description:** Figma-driven implementation workflow using the figma skill.
- **Use cases:** Figma URL to production UI, node-level context extraction, visual parity checks.
- **Repo / Source:** Local custom skill (no public repo documented).
- **Install / Access:** Use from `~/.codex/skills/figma/`. To get full value, pair it with Figma MCP and use design context + screenshot before implementation.

### 3) `test-driven-development`

- **Description:** TDD workflow with failing test first, minimal implementation second, refactor third.
- **Use cases:** New features, bug fixes, regression prevention.
- **Repo / Source:** https://github.com/obra/superpowers
- **Install / Access:** Use from `~/.codex/superpowers/skills/test-driven-development/` before writing implementation code.

### 4) `systematic-debugging`

- **Description:** Root-cause debugging process based on explicit hypotheses and verification.
- **Use cases:** Flaky tests, unknown regressions, hard-to-reproduce bugs.
- **Repo / Source:** https://github.com/obra/superpowers
- **Install / Access:** Use from `~/.codex/superpowers/skills/systematic-debugging/` before proposing fixes.

### 5) `verification-before-completion`

- **Description:** Requires fresh command evidence before claiming work is complete.
- **Use cases:** Pre-commit checks, pre-PR validation, preventing false completion claims.
- **Repo / Source:** https://github.com/obra/superpowers
- **Install / Access:** Use from `~/.codex/superpowers/skills/verification-before-completion/` before completion claims.

## Updates

- Weekly update: [`2026-W11`](updates/2026-W11.md)

## Profiles

- Instagram: https://instagram.com/rfischbackdev
- GitHub: https://github.com/RyanFischback
