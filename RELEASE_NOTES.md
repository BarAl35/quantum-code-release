# Quantum Code v1.1.7

Patch: Google Gemini provider, clearer MCP connection errors, and safer Windows installer upgrades.

## Added

- **Google Gemini** — first-class provider in Settings (API key via `GEMINI_API_KEY` / secrets store)

## Fixes

- **MCP** — show connection errors under each server row; retry corrupt GitLab npx caches with an isolated `--cache` dir
- **Windows installer** — unlock bundled `node.exe` before NSIS overwrite so upgrades are less likely to fail mid-install

## Downloads

- **Windows:** `downloads/v1.1.7/windows/`
- **macOS:** `downloads/v1.1.7/macos/` (build on a Mac or Actions)

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code if it is running, then run the new installer. Confirm **About → Version 1.1.7**.
