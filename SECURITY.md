# Security

- Do not commit tokens, private keys, API keys, or subscription URLs.
- Do not commit host names, user profile paths, or machine identifiers.
- Do not commit `.env` files or credential dumps.

## Hooks

This repository does not commit hook scripts. A file under `hooks/` or a client hook config would run in an agent session only after the workspace is trusted. Those files are not git `pre-commit` or `pre-push` hooks. Review any hook before enabling it. Do not enable hooks from an untrusted clone.
