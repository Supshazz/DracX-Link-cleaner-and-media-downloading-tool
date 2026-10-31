# Security Policy

## Supported release

Security fixes should be reported against the latest published DracX release.

## Reporting a vulnerability

Please do not publish credentials, cookies, access tokens, private media URLs, or exploit details in a public issue.

Contact the repository owner privately through GitHub to report a suspected vulnerability. Include a clear description, affected DracX and Windows versions, minimal reproduction steps, redacted logs, and potential impact.

## Security expectations

- DracX is designed for local use on the user's PC.
- Do not expose its local service ports to untrusted networks.
- Treat links, resolver responses, downloaded metadata and media as untrusted input.
- Do not disable TLS certificate verification to work around resolver failures.
- Never request or store users' browser cookies, account passwords or platform session tokens.

Please allow time for investigation and a coordinated fix before public disclosure.
