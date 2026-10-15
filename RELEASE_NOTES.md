# Quantum Code v1.1.10

Engine recovery when the sidecar dies, OpenAPI-to-API-tests multi-env auth (including paste-curl → `.env`), and a dedicated Heal test agent.

## Added

- **Engine watchdog** — detect a dead local engine, one automatic restart, then **Engine stopped** with Restart
- **OpenAPI multi-env** — `QC_ENV` (dev / test / uat / …), `$SWAGGER_URL`, Keycloak / Bearer / Basic from `.env` + `.env.${QC_ENV}`
- **Auth from curl** — paste a working curl; secrets/URLs merge into `.env.${QC_ENV}` and a `$ENV` script under `.quantumcode/scripts/`
- **Heal test** — `/heal-test` (and Pipelines **Heal test**): Command + Description → locate the failing test → fix → re-run
- **Secret hygiene** — ignore `.env.*` overlays and bundled `resources/agents|workflows`; tighter release secret scan

## Downloads

- **Windows:** `downloads/v1.1.10/windows/`
- **macOS (Apple Silicon only):** `downloads/v1.1.10/macos/` — after install run:

  ```bash
  xattr -cr "/Applications/Quantum Code.app"
  ```

Installers include **Node** and **JDK 21**. Git is optional ([git-scm.com](https://git-scm.com/)).

## Upgrade

Quit Quantum Code if it is running, then run the new installer / replace the `.app`. Confirm **About → Version 1.1.10**.
