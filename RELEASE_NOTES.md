# Quantum Code v1.1.9

Web mode as a conversation-first browser chat, clearer Tests Pass/Fail, and recent cockpit deepeners.

## Added

- **Web mode conversation shell** — full-width chat, project close (×), header **Open IDE** only (provider/model stay by the composer)
- **Tests Pass/Fail** — run outcome chips with ✓ / ✕, plus per-case Expected / Actual when the log has them
- **G16 Perf** — presets, script sync, and report verdict on the Tests Perf tab
- **G3 semantic search** — local hash-embedding search over the repo
- **G11 thin clients** — VS Code and JetBrains spikes talking to the engine (Status / Open / Act)

## Downloads

- **Windows:** `downloads/v1.1.9/windows/`
- **macOS (Apple Silicon only):** `downloads/v1.1.9/macos/` — after install run:

  ```bash
  xattr -cr "/Applications/Quantum Code.app"
  ```

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code if it is running, then run the new installer / replace the `.app`. Confirm **About → Version 1.1.9**.
