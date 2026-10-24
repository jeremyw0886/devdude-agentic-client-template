# AGENTS.md

## Project
Client project template for DevDudeJeremy LLC. Spec-driven delivery with AI agents.

## Commands
- Install: `npm install` (or your stack equivalent)
- Test: `npm test`
- Lint: `npm run lint`
- Build: `npm run build`

## Conventions
- Use TypeScript. Prefer named exports.
- Keep changes small and scoped to the written spec.
- Run tests and lint before considering a task done.
- Do not invent patterns; follow existing code and this file.
- Flag anything that touches auth, payments, or data models for human review.

## Layout
- `/src` — application code
- `/docs` — specs, architecture decisions, client briefs
- `/scripts` — verification and helper scripts

## Workflow
1. Read the current spec in `/docs/SPEC.md` (or equivalent).
2. Propose a plan if the task is multi-file.
3. Implement only what the acceptance criteria require.
4. Verify with tests/lint.
5. Summarize the diff for human review.

## Do Not
- Expand scope beyond the acceptance criteria.
- Modify files marked as high-risk without explicit approval.
- Commit secrets or credentials.
