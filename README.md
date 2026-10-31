# DracX - Link Cleaner + Downloading Tool

DracX is a Windows desktop application combining media-link inspection and downloading workflows with a privacy-focused share-link cleaner.

> **Current release:** v3.11.8 · Windows x64

## Highlights

- Native Windows desktop window (WebView2).
- Media workflows for TikTok, Instagram, YouTube and X.
- Automatic source-quality selection, with output capped at 4K.
- FFmpeg-based audio/video stream merging without lossy re-encoding.
- Share-link cleaning for supported tracking parameters.
- Local-first application backend.

Platform availability and resolver behaviour can change when third-party services change.

## Download DracX

Download the ready-to-run Windows executable from the [Releases](https://github.com/Supshazz/DracX-Link-cleaner-and-media-downloading-tool/releases) page.

The release includes the standalone EXE and SHA-256 checksum. Verify the checksum after downloading.

## Repository layout

- `DracX-App/` — application code, frontend, static assets, tests and service integration.
- `docs/` — build, development, privacy and troubleshooting documentation.
- `.github/workflows/` — automated source checks.
- Windows build scripts — build the native desktop application.

Generated build folders, virtual environments, runtime caches, downloaded dependencies, logs and user data do not belong in source control.

## Build and development

The executable is built on Windows. Follow the build documentation included in the repository for supported Python, Node.js, WebView2 and FFmpeg requirements.

Run the project's automated tests before submitting changes. Keep secrets, browser cookies, account tokens and private media links out of commits and issue reports.

## Privacy and responsible use

- DracX is intended to run locally on the user's PC.
- Do not expose its local service ports to the public internet.
- Some TikTok fallback routes may contact third-party resolver services; consult the privacy and third-party service documentation.
- Only download content you own or are authorized to save. Respect platform terms and applicable law.

## Third-party software

DracX integrates third-party projects such as yt-dlp, BgUtils, FFmpeg, pywebview and WebView2. Their respective notices and license files are retained with the relevant components. Each component remains subject to its own license.

The DracX project's own licensing status is described in [LICENSE-STATUS.md](LICENSE-STATUS.md). Do not assume all bundled components share one license.

## Reporting issues

Please include the DracX version, Windows version/architecture, affected platform, reproduction steps and a redacted log excerpt. Never include passwords, cookies, tokens or private links.

---

**Repository:** [Supshazz/DracX-Link-cleaner-and-media-downloading-tool](https://github.com/Supshazz/DracX-Link-cleaner-and-media-downloading-tool)
