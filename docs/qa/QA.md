# QA Rules

## Quality Bar

### Questions
- What does “good enough for MVP” mean?
- What bugs block release?
- What bugs can wait?
- What should be checked before every commit?

## Edge Cases

### Questions
- What happens with empty data?
- What happens with very long text?
- What happens with duplicate entries?
- What happens with bad internet?
- What happens if the user refreshes mid-action?

## Regression Rules

- Do not break completed flows.
- Test core flow after every major change.
- Add issues to `QA_LOG.md`.
- Update `DONE.md` only after verification.
