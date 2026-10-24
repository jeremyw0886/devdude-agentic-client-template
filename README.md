# DevDudeJeremy Agentic Client Template

Starter template for spec-driven, multi-agent client delivery workflows.

Your Mac Studio M3 Ultra + OWC StudioStack already has the horsepower. This template gives the process structure so agents stay reliable and you stay in control.

## Files
- `AGENTS.md` — Shared rules read by most coding agents (commands, conventions, layout, workflow).
- `CLAUDE.md` — Claude Code import of AGENTS.md plus Claude-specific notes.
- `docs/SPEC.md` — Example acceptance-criteria spec template.
- `docs/CLIENT-OPS.md` — Ideas for automating intake, proposals, and follow-ups (n8n-friendly).

## How to use
1. Clone or copy this repo as the starting point for a new client project.
2. Fill in `docs/SPEC.md` with the actual goal and acceptance criteria.
3. Point your agent (Claude Code, Cursor, etc.) at the repo.
4. Keep changes small, verify, and review the diff.
5. Update AGENTS.md when you discover a recurring convention worth codifying.

## Recommended loop
Brief → written Spec → Plan → Agent implementation → Tests/lint → Human review → Delivery.

Start with one real client project and measure the time difference. The biggest gains come from the discipline of the spec + verification, not from more tools.
