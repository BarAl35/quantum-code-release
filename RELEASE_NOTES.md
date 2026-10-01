# Quantum Code v1.1.2

Patch release: first-install engine finds the bundled `engine.mjs` under the Windows installer layout.

## Fixes

- **Bundled engine path** — installed apps look up `resources/engine.mjs` (and bundled Node under `resources/nodejs/`), matching the NSIS/MSI layout. Fresh installs no longer show “Bundled engine.mjs not found” when the file is already on disk.
- **GitHub release script** — missing tags no longer abort create; installer paths with spaces upload correctly.

## Downloads

- **Windows:** `downloads/v1.1.2/windows/`
- **macOS:** `downloads/v1.1.2/macos/` (build on a Mac or Actions)

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code fully, then run the new installer. Confirm **About → Version 1.1.2**.
