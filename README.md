# Quantum Code — downloads

**Language / Dil:** English · [Türkçe](#türkçe)

This repository contains **installers and release notes only**. There is **no source code** here. For development, use the private/main product repository (not published).

---

## Download

**Recommended:** **[Release v1.1.4](https://github.com/BarAl35/quantum-code-release/releases/tag/v1.1.4)** (Windows `.exe` / `.msi`). **macOS (Apple Silicon):** [Release v1.1.7](https://github.com/BarAl35/quantum-code-release/releases/tag/v1.1.7) (`.dmg`).

**Current Windows build:** [`downloads/v1.1.4/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.4/windows) (`.exe`, `.msi`).

| Platform | Path |
| --- | --- |
| Windows (latest) | [`downloads/v1.1.4/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.4/windows) |
| Windows (previous) | [`downloads/v1.1.3/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.3/windows) |
| Windows (legacy) | [`downloads/v0.1.0/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v0.1.0/windows) |
| macOS (Apple Silicon only) | [`downloads/v1.1.7/macos/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.7/macos) (`Quantum Code_1.1.7_aarch64.dmg`) |

Verify with `SHA256SUMS.txt` in the repo root.

---

## Before you install

1. **You do not need Node.js or a JDK on your PC.** **v0.1.1+ / v1.1.4** installers ship a private **Node** runtime and **JDK 21** (Temurin) inside the app — Settings, Ask AI, and Java projects use those.
2. Install **Git** only if you use Git inside the app (not bundled; [git-scm.com](https://git-scm.com/download/win)).
3. **Do not use v0.1.0** — that old build expected Node on PATH, so Settings / Open Folder often failed. Always install **v1.1.4+** from Releases.

---

## Windows

1. Download `Quantum Code_*_x64-setup.exe` from Releases.
2. **Upgrade from v0.1.0 / v0.1.1:** Quit Quantum Code (check Task Manager — no `Quantum Code` or stray `node` on port 47821). Either run the **new installer** (it replaces the same app id) or uninstall first (below), then install.
3. Run the installer (current-user install; admin usually not required).
4. Open **Quantum Code** from the Start menu. Check **About** for version **1.1.4+** if Settings failed on an older build.
5. If SmartScreen warns about an unknown publisher, choose **More info → Run anyway** (unsigned community build).

**Uninstall old version:** **Settings → Apps → Installed apps → Quantum Code → Uninstall** (or **Apps → Quantum Code → Uninstall**). Your projects and `~/.quantumcode` settings stay on disk; only the app is removed. Existing `.aiforge` settings are migrated on first launch. Then install the latest Release `.exe`.

---

## macOS

> **Apple Silicon only (M1 / M2 / M3 / M4).** Intel Macs are not supported at the moment.

1. Download `Quantum Code_*_aarch64.dmg` from Releases (or [`downloads/v1.1.7/macos/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.7/macos)).
2. Open the `.dmg` and drag **Quantum Code** to **Applications**.
3. The app is not notarized, so macOS may say it is "damaged" or "can't be opened". Open **Terminal** and run:

   ```bash
   xattr -cr "/Applications/Quantum Code.app"
   ```

4. Open **Quantum Code** from Applications / Launchpad.

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

1. **Node.js veya JDK kurmanız gerekmez** — **v0.1.1+ / v1.1.4** kurulum dosyası kendi Node ve JDK 21’ini taşır.
2. Uygulama içi Git için isteğe bağlı **Git**.
3. **v0.1.0 kullanmayın** (PATH’te Node istiyordu; Settings açılmazdı). **v1.1.4+** indirin.

### Windows

1. Releases’ten `Quantum Code_*_x64-setup.exe` indirin.
2. Kurulumu çalıştırın.
3. Başlat menüsünden **Quantum Code**’u açın.
4. SmartScreen uyarısı: **More info → Run anyway**.

Kaldırma: **Ayarlar → Uygulamalar → Quantum Code**.

### macOS

> **Şu anda yalnızca Apple Silicon (M1 / M2 / M3 / M4) destekleniyor.** Intel Mac desteği yok.

1. Releases’ten (veya [`downloads/v1.1.7/macos/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.7/macos)) `Quantum Code_*_aarch64.dmg` dosyasını indirin.
2. `.dmg`’yi açıp **Quantum Code**’u **Applications** (Uygulamalar) klasörüne sürükleyin.
3. Uygulama notarize edilmediği için macOS “hasarlı” veya “açılamıyor” uyarısı verebilir. **Terminal**’i açıp şunu çalıştırın:

   ```bash
   xattr -cr "/Applications/Quantum Code.app"
   ```

4. **Quantum Code**’u Uygulamalar / Launchpad’den açın.

### Linux

Releases’teki `.deb` veya `.AppImage` dosyasını kullanın; sistemde Node şart değildir (paketli runtime).

### İlk kullanım

Klasör açın, **Settings**’ten sağlayıcı/model ayarlayın, **Ask AI** ve **Terminal** ile devam edin.

---

**Product:** Quantum Code · **Version:** see latest [Release tag](https://github.com/BarAl35/quantum-code-release/releases)
