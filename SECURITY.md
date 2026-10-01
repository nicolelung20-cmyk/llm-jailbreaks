# Security Policy

## Reporting a vulnerability

Please report vulnerabilities privately through GitHub's
["Report a vulnerability"](../../security/advisories/new) form on this
repository's Security tab. Do not open a public issue for security problems.

You can expect an acknowledgement within 7 days.

## Handling secrets

- Never commit API keys, tokens, private keys or `.env` files.
- Use environment variables or your host's secret store.
- If a secret is committed, rotate it immediately; deleting it from history is not enough.
