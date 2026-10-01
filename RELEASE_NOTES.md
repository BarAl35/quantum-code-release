# Quantum Code v1.1.4

Patch: GitHub/GitLab MCP auth and Windows upgrade when `node.exe` is locked.

## Fixes

- **GitHub MCP** — resolve `${GITHUB_TOKEN}` / strip accidental `Bearer` paste so Connect no longer returns “Authorization header is badly formatted”
- **GitLab MCP** — default `+ gitlab` uses `@zereight/mcp-gitlab` with `GITLAB_TOKEN` (official `/api/v4/mcp` is OAuth-only and rejects PATs)
- **Windows installer** — NSIS pre-install kills Quantum Code + bundled engine `node.exe` so upgrades are not blocked on `resources\nodejs\node.exe`

## Downloads

- **Windows:** `downloads/v1.1.4/windows/`
- **macOS:** `downloads/v1.1.4/macos/` (build on a Mac or Actions)

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code if it is running (Task Manager: `Quantum Code` / stray `node`), then run the new installer. Confirm **About → Version 1.1.4**.
