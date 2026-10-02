# Quantum Code — downloads

**Language / Dil:** English · [Türkçe](#türkçe)

This repository contains **installers and release notes only**. There is **no source code** here. For development, use the private/main product repository (not published).

---

## Download

**Recommended:** **[Release v1.1.8](https://github.com/BarAl35/quantum-code-release/releases/tag/v1.1.8)** — Windows (`.exe` / `.msi`) and **macOS Apple Silicon** (`.dmg`).

| Platform | Path |
| --- | --- |
| Windows (latest) | [`downloads/v1.1.8/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.8/windows) |
| Windows (previous) | [`downloads/v1.1.7/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.7/windows) |
| macOS (Apple Silicon only) | [`downloads/v1.1.8/macos/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.8/macos) (`Quantum Code_*_aarch64.dmg`) |
| Windows (older) | [`downloads/v1.1.4/windows/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.4/windows) |

Verify with `SHA256SUMS.txt` on the Release (and in the release branch).

---

## Before you install

1. **You do not need Node.js or a JDK on your PC.** **v0.1.1+** installers ship a private **Node** runtime and **JDK 21** (Temurin) inside the app — Settings, Ask AI, and Java projects use those.
2. Install **Git** only if you use Git inside the app (not bundled; [git-scm.com](https://git-scm.com/download/win) / [git-scm.com/download/mac](https://git-scm.com/download/mac)).
3. **Do not use v0.1.0** — that old build expected Node on PATH. Always install **v1.1.8+** from Releases.

---

## Windows

1. Download `Quantum Code_*_x64-setup.exe` from **[v1.1.8](https://github.com/BarAl35/quantum-code-release/releases/tag/v1.1.8)**.
2. **Upgrade:** Quit Quantum Code (check Task Manager — no `Quantum Code` or stray `node` on port 47821). Run the new installer (same app id) or uninstall first, then install.
3. Run the installer (current-user install; admin usually not required).
4. Open **Quantum Code** from the Start menu. Confirm **About → Version 1.1.8**.
5. If SmartScreen warns about an unknown publisher, choose **More info → Run anyway** (unsigned community build).

**Uninstall:** **Settings → Apps → Installed apps → Quantum Code → Uninstall**. Projects and `~/.quantumcode` settings stay on disk.

---

## macOS

> **Apple Silicon only (M1 / M2 / M3 / M4).** Intel Macs are **not** supported right now.
>
> macOS users **can open the app** after clearing quarantine attributes (the build is not notarized).

1. Download `Quantum Code_*_aarch64.dmg` from **[v1.1.8](https://github.com/BarAl35/quantum-code-release/releases/tag/v1.1.8)** (or [`downloads/v1.1.8/macos/`](https://github.com/BarAl35/quantum-code-release/tree/main/downloads/v1.1.8/macos)).
2. Open the `.dmg` and drag **Quantum Code** to **Applications**.
3. If macOS says the app is “damaged” or “can’t be opened”, open **Terminal** and run:

   ```bash
   xattr -cr "/Applications/Quantum Code.app"
   ```

4. Open **Quantum Code** from Applications / Launchpad. Confirm **About → Version 1.1.8**.

---

## Linux

1. Download `.deb` or `.AppImage` from Releases when published.
2. **deb:** `sudo dpkg -i …deb` then `sudo apt-get install -f` if needed.
3. **AppImage:** `chmod +x` and run.

Bundled Node/JDK apply when those packages ship; otherwise ensure `node` 22+ is on PATH.

---

## First launch

1. Open a project folder (**Open Folder**).
2. In **Settings**, configure your AI **provider** and **model** (API keys stay on your machine).
3. Use **Ask AI**, **Terminal**, and **Explorer** from the workbench.

---

## Support

- Install issues: quit fully and reopen so nothing is stuck on port **47821**.
- **macOS Gatekeeper:** run `xattr -cr "/Applications/Quantum Code.app"` after install.
- This repo is **distribution only** — no source code here.

---

## Türkçe

Bu depoda **yalnızca kurulum dosyaları ve sürüm notları** vardır. **Kaynak kod yoktur.**

### İndirme

**Önerilen:** **[Release v1.1.8](https://github.com/BarAl35/quantum-code-release/releases/tag/v1.1.8)** — Windows + **macOS Apple Silicon**.

### Kurulum öncesi

1. **Node.js veya JDK kurmanız gerekmez** — kurulum dosyası kendi Node ve JDK 21’ini taşır.
2. Uygulama içi Git için isteğe bağlı **Git**.
3. **v0.1.0 kullanmayın.** **v1.1.8+** indirin.

### Windows

1. Releases’ten `Quantum Code_*_x64-setup.exe` indirin.
2. Kurulumu çalıştırın.
3. Başlat menüsünden **Quantum Code**’u açın (**About → 1.1.8**).
4. SmartScreen: **More info → Run anyway**.

### macOS

> **Şu anda yalnızca Apple Silicon (M1 / M2 / M3 / M4) destekleniyor.** Intel Mac yok.
>
> macOS kullanıcıları uygulamayı açabilir; notarize edilmediği için aşağıdaki komut gerekir.

1. Releases’ten `Quantum Code_*_aarch64.dmg` indirin.
2. `.dmg`’yi açıp **Quantum Code**’u **Applications** klasörüne sürükleyin.
3. “Hasarlı” / “Açılamıyor” uyarısı için **Terminal**:

   ```bash
   xattr -cr "/Applications/Quantum Code.app"
   ```

4. Uygulamayı Launchpad / Applications’tan açın.

### Linux

Releases’teki `.deb` veya `.AppImage` (yayınlandığında).

### İlk kullanım

Klasör açın, **Settings**’ten sağlayıcı/model ayarlayın, **Ask AI** ve **Terminal** ile devam edin.

---

**Product:** Quantum Code · **Latest:** [v1.1.8](https://github.com/BarAl35/quantum-code-release/releases/tag/v1.1.8)
