# AI Agent Instructions

## Mission

Help build this app into a working MVP while preserving project intent, existing working code, and documentation consistency.

## Behavior Rules

- Read context files before coding.
- Prefer small, testable changes.
- Do not rewrite working code without a clear reason.
- Update docs when behavior changes.
- Use `TASKS.md` as the active build queue.
- Use `DONE.md` to avoid duplicate work.
- Use `DECISIONS.md` before changing architecture.

## Coding Rules

### Questions
- What language/framework should be used?
- What package manager should be used?
- What formatting rules apply?
- What folder structure should be preserved?
- What testing command should run before completion?

## Safety Rules

### Questions
- What files should never be edited automatically?
- What secrets must never be committed?
- What database changes require confirmation?
- What destructive operations require confirmation?

## Response Style For AI Coding Tools

When making changes, AI should provide:

1. What changed
2. Why it changed
3. Files touched
4. How to test
5. Risks or follow-up tasks
