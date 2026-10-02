# Quantum Code v1.1.8

Ask AI Chat/Plan/Act handoff, clearer live status, and public macOS Apple Silicon install notes.

## Added

- **Ask AI Apply handoff** — after Chat or Plan finishes, switch to Act with an **Apply** primary action
- **Live status line** — short “doing this now” text instead of the Progress panel
- **Context / Agent** labels that spell out what to include and who runs the task
- **macOS (Apple Silicon)** — public install path documented; clear Gatekeeper quarantine with `xattr`

## Fixes

- **macOS JDK layout** — bundled Temurin `Contents/Home` resolution for Java tools on Apple Silicon builds

## Downloads

- **Windows:** `downloads/v1.1.8/windows/`
- **macOS (Apple Silicon only):** `downloads/v1.1.8/macos/` — after install run:

  ```bash
  xattr -cr "/Applications/Quantum Code.app"
  ```

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code if it is running, then run the new installer / replace the `.app`. Confirm **About → Version 1.1.8**.
