# MVP Context Template

Use this repo as the **context brain** for an AI-assisted MVP build.

## Purpose

This template helps you collect the information Cursor, Claude Code, Codex, or another AI coding agent needs before building.

Fill out the markdown files first. Then tell your AI coding tool:

> Read this repo. Treat these markdown files as the source of truth. Ask only for missing blockers. Build Phase 1 from `TASKS.md` without changing completed work unless needed.

## Recommended Flow

1. Fill `PROJECT_INTAKE.md` first.
2. Fill `PRD.md` second.
3. Fill `TASKS.md` third.
4. Fill the docs in `/docs` as needed.
5. Use `.cursor/rules.md` as the AI behavior guide.
6. Start implementation only after Phase 1 is clear.

## Minimum Files To Complete Before Coding

- `PROJECT_INTAKE.md`
- `PRD.md`
- `TASKS.md`
- `AGENT.md`
- `docs/engineering/ARCHITECTURE.md`
- `docs/design/UI_UX.md`
- `docs/engineering/DATA_MODEL.md`
- `docs/qa/TESTING.md`

## Rule

If a question is hard to answer, write:

> AI may infer from project context.

Do not leave important sections blank.
