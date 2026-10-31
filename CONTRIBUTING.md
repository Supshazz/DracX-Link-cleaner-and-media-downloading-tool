# Contributing to DracX

Thanks for taking the time to improve DracX.

## Before making changes

1. Check existing issues and discussions for related work.
2. Keep changes focused and explain the user-facing reason.
3. Do not include credentials, browser cookies, private URLs, downloaded media, runtime logs containing personal data, or local machine paths.
4. Preserve third-party license notices and attribution.

## Development expectations

- Keep the local-only security model intact. Do not expose the local API server on public interfaces.
- Validate all user-supplied URLs and avoid introducing arbitrary file or network access.
- Preserve original media quality; avoid lossy re-encoding unless explicitly requested by the user.
- Keep platform-specific resolver behaviour isolated and diagnosable.
- Add or update regression tests for bug fixes.
- Keep generated build outputs and downloaded dependencies out of source control.

## Pull requests

Include a concise summary, reason for the change, relevant test results, screenshots for UI changes, and any platform or dependency limitations.

Do not claim a platform fix is verified unless it has been tested against the affected platform.
