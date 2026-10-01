# Quantum Code v1.1.1

Patch release: first-install engine so Open Folder and Settings work without system Node.

## Fixes

- **Engine sidecar** starts with HTTP `/health` checks (not TCP-only), longer cold-start wait, and sidecar logs
- **Restart Engine** from the error banner and Settings when `:47821` is down
- **Open Folder** ensures the engine is running before opening a workspace
- **Settings** recovers with Restart Engine / Appearance offline path
- MCP boot no longer blocks the engine for up to 60s per server
- Docs clarify: **end users do not need Node.js on PATH** (bundled since v0.1.1; do not use v0.1.0)

## Downloads

- **Windows:** `downloads/v1.1.1/windows/`
- **macOS:** `downloads/v1.1.1/macos/` (build on a Mac or Actions)

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code fully, then run the new installer (same app id). If Settings never loaded on an older build, confirm **About → Version 1.1.1**.
