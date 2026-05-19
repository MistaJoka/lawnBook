# Security

## Security Goals

### Questions
- What data must stay private?
- Who should access the app?
- Does the app need login?
- Does the app store customer data?
- Does the app store payment data?

## Secrets

Rules:

- Never commit `.env`.
- Use `.env.example` for placeholders.
- Rotate exposed keys immediately.

### Questions
- What API keys are required?
- Where are secrets stored locally?
- Where are secrets stored in production?

## Permissions

### Questions
- What roles exist?
- What can each role do?
- What should regular users never access?
- What admin actions require confirmation?

## Threats

### Questions
- What would happen if someone accessed another user's data?
- What actions could cause data loss?
- What abuse patterns are possible?
- What logging is needed for investigation?
