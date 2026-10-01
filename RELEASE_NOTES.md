# Quantum Code v1.1.6

Patch: Explorer hide/exclude reliability, `node_modules` visibility, and header chrome cleanup.

## Fixes

- **Explorer** — Harden **Hide in Explorer**; add **Exclude file/folder**, **Show all**, and **Include file/folder** on right-click
- **Always show** — Hiding a path that was kept visible by Always show now clears the conflicting pattern so the item actually disappears
- **node_modules** — No longer forced into the file tree for Node projects when excluded files are hidden; browse packages under **Libraries** instead (Show all still expands `node_modules` in the tree)
- **Header** — Remove the horizontal scrollbar that appeared under crowded menu rows

## Downloads

- **Windows:** `downloads/v1.1.6/windows/`
- **macOS:** `downloads/v1.1.6/macos/` (build on a Mac or Actions)

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code if it is running, then run the new installer. Confirm **About → Version 1.1.6**.
