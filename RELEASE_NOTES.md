# Quantum Code v1.1.3

GitLab connections + stronger Cucumber runs from the workbench.

## Highlights

- **GitLab token** in Settings → Connections (`GITLAB_TOKEN`) for Open MR when origin is GitLab
- **GitLab MCP** preset — `https://gitlab.com/api/v4/mcp` (same idea as GitHub Copilot MCP); Connect via OAuth or token
- **Cucumber / BDD** — Run feature discovers `src/features/**/steps`, enables `tsx` for TypeScript steps, and prints a tip when steps are Undefined
- **Anthropic (Claude)** Settings note: use Console API keys for company use (not Claude.ai browser login)

## Downloads

- **Windows:** `downloads/v1.1.3/windows/`
- **macOS:** `downloads/v1.1.3/macos/` (build on a Mac or Actions)

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code fully, then run the new installer. Confirm **About → Version 1.1.3**.
