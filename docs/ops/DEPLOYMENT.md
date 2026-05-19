# Deployment

## Deployment Target

### Questions
- Where will the app be hosted?
- Is this local-only, private, or public?
- Does it need a custom domain?
- Does it need HTTPS?

## Environment Variables

| Variable | Purpose | Required |
|---|---|---|
| EXAMPLE_KEY | Example only | no |

## Deployment Checklist

- [ ] Build succeeds locally
- [ ] Environment variables configured
- [ ] Database connected
- [ ] Auth configured if needed
- [ ] Domain configured if needed
- [ ] Core flow tested in production

## Advanced Questions

- What rollback plan exists?
- What logs are available?
- What uptime expectation exists?
- What monitoring is required?
- What backup plan exists?
