# Quantum Code — downloads

**Language / Dil:** English · [Türkçe](#türkçe)

This repository contains **installers and release notes only**. There is **no source code** here. For development, use the private/main product repository (not published).

---

## Download

Go to **[Releases](https://github.com/BarAl35/quantum-code-release/releases)** and download the installer for your operating system.

| Platform | File (example) |
| --- | --- |
| Windows | `Quantum Code_*_x64-setup.exe` |
| Windows (optional) | `Quantum Code_*_x64_en-US.msi` |
| macOS | `.dmg` in the release assets |
| Linux | `.deb` or `.AppImage` in the release assets |

Verify downloads with `SHA256SUMS.txt` in the same release (when provided).

---

## Before you install

1. **Node.js 22 or newer** must be installed and on your **PATH** (`node -v`).
   - Windows: [https://nodejs.org/](https://nodejs.org/)
2. Install **Git** if you use Git features inside the app (recommended).
3. For **Java projects**: JDK 21+ on the machine (the app can guide you; not bundled in v0.1).

---

## Windows

1. Download `Quantum Code_*_x64-setup.exe` from Releases.
2. Run the installer (current-user install; admin usually not required).
3. Open **Quantum Code** from the Start menu.
4. If SmartScreen warns about an unknown publisher, choose **More info → Run anyway** (unsigned community build).

Uninstall: **Settings → Apps → Quantum Code**.

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

**[Releases](https://github.com/BarAl35/quantum-code-release/releases)** sayfasından işletim sisteminize uygun dosyayı indirin.

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
