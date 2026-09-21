# Quantum Code — downloads

**Language / Dil:** English · [Türkçe](#türkçe)

This repository contains **installers and release notes only**. There is **no source code** here. For development, use the private/main product repository (not published).

---

## Download

**Recommended:** **[Release v0.1.4](https://github.com/BarAl35/quantum-code-release/releases/tag/v0.1.4)** (Windows `.exe` / `.msi`; macOS when added).

**Current Windows build:** [`downloads/v0.1.4/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v0.1.4/windows) (`.exe`, `.msi`).

| Platform | Path |
| --- | --- |
| Windows (latest) | [`downloads/v0.1.4/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v0.1.4/windows) |
| Windows (previous) | [`downloads/v0.1.3/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v0.1.3/windows) |
| Windows (legacy) | [`downloads/v0.1.0/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v0.1.0/windows) |
| macOS | `.dmg` on **Releases** when published (`downloads/v0.1.4/macos/`) |

Verify with `SHA256SUMS.txt` in the repo root.

---

## Before you install

1. **v0.1.1+** installers include **Node** and **JDK 21** (Temurin) — no separate setup for Settings, AI, or Java projects.
2. Install **Git** only if you use Git inside the app (not bundled; [git-scm.com](https://git-scm.com/download/win)).
3. **v0.1.0** required Node on PATH; upgrade if Settings never loaded.

---

## Windows

1. Download `Quantum Code_*_x64-setup.exe` from Releases.
2. **Upgrade from v0.1.0 / v0.1.1:** Quit Quantum Code (check Task Manager — no `Quantum Code` or stray `node` on port 47821). Either run the **new installer** (it replaces the same app id) or uninstall first (below), then install.
3. Run the installer (current-user install; admin usually not required).
4. Open **Quantum Code** from the Start menu. Check **About** for version **0.1.4+** if Settings failed on an older build.
5. If SmartScreen warns about an unknown publisher, choose **More info → Run anyway** (unsigned community build).

**Uninstall old version:** **Settings → Apps → Installed apps → Quantum Code → Uninstall** (or **Apps → Quantum Code → Uninstall**). Your projects and `~/.quantumcode` settings stay on disk; only the app is removed. Existing `.aiforge` settings are migrated on first launch. Then install the latest Release `.exe`.

---

## macOS

1. Download the `.dmg` from Releases.
2. Drag **Quantum Code** to Applications.
3. If Gatekeeper blocks the app, use **Open** from the context menu or allow in **Privacy & Security**.

---

## Linux

1. Download `.deb` or `.AppImage` from Releases.
2. **deb:** `sudo dpkg -i …deb` then `sudo apt-get install -f` if needed.
3. **AppImage:** `chmod +x` and run.

Ensure `node` 22+ is on PATH.

---

## First launch

1. Open a project folder (**Open Folder**).
2. In **Settings**, configure your AI **provider** and **model** (API keys stay on your machine).
3. Use **Ask AI**, **Terminal**, and **Explorer** from the workbench.

---

## Support

- Install issues: check Node version and that no old engine is stuck on port **47821** (quit the app fully and reopen).
- This repo is **distribution only** — do not expect source or issue fixes here unless linked from release notes.

---

## Türkçe

Bu depoda **yalnızca kurulum dosyaları ve sürüm notları** vardır. **Kaynak kod yoktur.**

### İndirme

**[Releases](https://github.com/BarAl35/quantum-code-release/releases)** (Windows + macOS) veya **`release/v0.1.0`** dalındaki `downloads/v0.1.0/windows/` ve `downloads/v0.1.0/macos/` klasörleri.

### Kurulum öncesi

1. **Node.js 22+** kurulu olmalı ve `node -v` çalışmalı.
2. Git özellikleri için **Git** önerilir.
3. Java projeleri için makinede **JDK 21+** gerekir.

### Windows

1. Releases’ten `Quantum Code_*_x64-setup.exe` indirin.
2. Kurulumu çalıştırın.
3. Başlat menüsünden **Quantum Code**’u açın.
4. SmartScreen uyarısı: **More info → Run anyway**.

Kaldırma: **Ayarlar → Uygulamalar → Quantum Code**.

### macOS / Linux

Releases’teki `.dmg`, `.deb` veya `.AppImage` dosyasını kullanın; Node 22+ şarttır.

### İlk kullanım

Klasör açın, **Settings**’ten sağlayıcı/model ayarlayın, **Ask AI** ve **Terminal** ile devam edin.

---

**Product:** Quantum Code · **Version:** see latest [Release tag](https://github.com/BarAl35/quantum-code-release/releases)
