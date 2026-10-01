# Quantum Code v1.1.5

Patch: terminal reliability and history, Ask panel resize, Cucumber step loading, and GitLab MCP Windows install races.

## Fixes

- **Terminal** — second tab / pop-out opens fresh (no Console log bleed); `clear` / `cls` clears scrollback; ↑/↓ recalls the last 50 commands; Windows shell stays on reliable `cmd.exe` (PowerShell via `QUANTUM_SHELL` if wanted); common JDK paths on PATH
- **Ask AI** — drag to resize form vs chat; wider Ask dock defaults so chat is not crushed
- **package.json** — CodeLens / hover **Run Script** runs `npm run …` in the Terminal
- **Cucumber / Tests** — merge `cucumber.js` imports with discovered step folders; monorepo package root; brace-glob expand; try `npx -p tsx` when TypeScript steps lack a local `tsx`
- **GitLab MCP** — per-server isolated npm cache under `~/.quantumcode/mcp-npx-cache` with ENOTEMPTY retry; drop `@latest` to reduce Windows npx races

## Downloads

- **Windows:** `downloads/v1.1.5/windows/`
- **macOS:** `downloads/v1.1.5/macos/` (build on a Mac or Actions)

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code if it is running, then run the new installer. Confirm **About → Version 1.1.5**.
