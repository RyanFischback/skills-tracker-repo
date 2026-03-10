# Skills Tracker Template (Weekly + Monthly)

Owner: `[Your Name]`  
Last Updated: `[YYYY-MM-DD]`  
Audience: `[Team / Clients / Internal]`  
Cadence: `Weekly + Monthly`

## Why This Format

Use this as a living doc that supports:

1. Stable reference for your core skills.
2. Weekly updates for what is currently highest impact.
3. Monthly updates for new skills and process changes.

## Recommended Source of Truth

Yes, this is better hosted on GitHub as the source of truth.

- Keep this file in-repo and share the Google Doc as a read-friendly mirror.
- Update via PRs so you have version history and clear ownership.
- Link weekly/monthly update files from this doc.

Suggested GitHub structure:

```text
docs/
  skills/
    skills-directory.md
    updates/
      2026/
        2026-W11.md
        2026-W12.md
        2026-03.md
```

## Core Skill Inventory (Top 5)

| Skill | Description | High-Value Use Cases | Repo / Source | Install or Access Instructions |
| --- | --- | --- | --- | --- |
| `linear` | Structured Linear project and issue management via MCP. | Sprint planning; bug triage; bulk updates; project tracking. | Local custom skill (no public repo documented). | Use from `~/.codex/skills/linear/`. MCP setup: `codex mcp add linear --url https://mcp.linear.app/mcp`, enable `rmcp_client`, then `codex mcp login linear`. Restart Codex after login. |
| `figma` | Uses Figma MCP for design context, screenshots, assets, and design-to-code execution. | Figma URL to production UI; node-level context extraction; visual parity checks. | Local custom skill (no public repo documented). | Use from `~/.codex/skills/figma/`. Configure MCP and use design context + screenshot before implementation. |
| `test-driven-development` | TDD workflow: failing test first, minimal implementation, then refactor. | New features; bug fixes; regression prevention. | Local superpower skill (no public repo documented). | Use from `~/.codex/superpowers/skills/test-driven-development/` before writing implementation code. |
| `systematic-debugging` | Root-cause debugging process based on explicit hypotheses and verification. | Flaky tests; unknown regressions; hard-to-reproduce bugs. | Local superpower skill (no public repo documented). | Use from `~/.codex/superpowers/skills/systematic-debugging/` before proposing fixes. |
| `verification-before-completion` | Requires fresh command evidence before claiming work is complete. | Pre-commit checks; pre-PR validation; preventing false completion claims. | Local superpower skill (no public repo documented). | Use from `~/.codex/superpowers/skills/verification-before-completion/` before completion claims. |

## Weekly Update Block (Copy/Paste Each Week)

### Week of `[YYYY-MM-DD]`

- Top Skills This Week: `[skill 1]`, `[skill 2]`, `[skill 3]`
- New Skill Added This Week: `[none or skill name]`
- Biggest Win: `[1-2 lines]`
- Current Bottleneck: `[1-2 lines]`
- Next Week Focus: `[what changes]`
- Evidence Links: `[PRs / docs / issues]`

## Monthly Update Block (Copy/Paste Each Month)

### Month `[YYYY-MM]`

- Top 5 Skills This Month (ranked):
1. `[skill]`
2. `[skill]`
3. `[skill]`
4. `[skill]`
5. `[skill]`

- New Skills Introduced: `[list]`
- Retired/Deprioritized Skills: `[list]`
- Process Improvements from Skills: `[1-3 bullets]`
- Next Month Skill Goals: `[1-3 bullets]`

## Change Log Index

| Period | Update Type | Owner | Link |
| --- | --- | --- | --- |
| `[2026-W11]` | Weekly | `[name]` | `[link]` |
| `[2026-03]` | Monthly | `[name]` | `[link]` |
