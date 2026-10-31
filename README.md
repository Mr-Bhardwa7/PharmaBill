# PharmaBill — Desktop Binary Releases

<div align="center">

![PharmaBill](https://img.shields.io/badge/PharmaBill-Desktop%20POS-008080?style=for-the-badge&logo=mediamarkt&logoColor=white)
![Release](https://img.shields.io/github/v/release/Mr-Bhardwa7/PharmaBill?style=for-the-badge&color=blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Ubuntu%20%7C%20Linux-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)

**Official binary distribution repository for PharmaBill — Next-Generation Pharmacy Point of Sale & Inventory Management System.**

[🌐 Official Website & Web Portal](https://pharmabill.in) • [📦 Latest Releases](https://github.com/Mr-Bhardwa7/PharmaBill/releases) • [📝 Release Changelog](CHANGELOG.md) • [🐞 Report an Issue](https://github.com/Mr-Bhardwa7/PharmaBill/issues)

</div>

---

## 📌 About This Repository

This repository is dedicated **exclusively to official compiled desktop builds, installers, and release packages** for PharmaBill. 

Our official web portal and desktop auto-update service dynamically fetch verified application builds and metadata from this repository.

> **Note**: The core source code of PharmaBill is proprietary. This repository hosts only signed release binaries and installation documentation.

---

## ⬇️ Download Links

Always download official binaries directly from [GitHub Releases](https://github.com/Mr-Bhardwa7/PharmaBill/releases/latest).

| Operating System | Package Type | Architecture | Direct Download |
| :--- | :--- | :--- | :--- |
| **Windows 10 / 11** | Installer (`.exe`) | 64-bit (x64) | [Download for Windows](https://github.com/Mr-Bhardwa7/PharmaBill/releases/latest) |
| **Ubuntu / Debian** | Debian Package (`.deb`) | 64-bit (`amd64`) | [Download .deb](https://github.com/Mr-Bhardwa7/PharmaBill/releases/latest) |
| **Linux (Universal)** | AppImage (`.AppImage`) | 64-bit (`amd64`) | [Download .AppImage](https://github.com/Mr-Bhardwa7/PharmaBill/releases/latest) |

---

## 🚀 Installation Guide

### 🪟 Windows (10 / 11)
1. Download the `pharmabill_<version>_x64-setup.exe` installer from [Releases](https://github.com/Mr-Bhardwa7/PharmaBill/releases/latest).
2. Double-click the `.exe` file to start the installation wizard.
3. Follow the on-screen instructions and launch PharmaBill from the Start Menu or Desktop shortcut.

### 🐧 Ubuntu / Debian (`.deb`)
1. Download the `pharmabill_<version>_amd64.deb` file.
2. Install via terminal:
   ```bash
   sudo dpkg -i pharmabill_*_amd64.deb
   sudo apt-get install -f # resolve any missing dependencies if needed
   ```
3. Launch PharmaBill from your application launcher or type `pharmabill` in your terminal.

### 📦 Universal Linux (`.AppImage`)
1. Download `pharmabill_<version>_amd64.AppImage`.
2. Make the file executable:
   ```bash
   chmod +x pharmabill_*_amd64.AppImage
   ```
3. Run the application:
   ```bash
   ./pharmabill_*_amd64.AppImage
   ```

---

## 💻 System Requirements

| Specification | Minimum | Recommended |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 (64-bit) / Ubuntu 20.04+ / Debian 11+ | Windows 11 / Ubuntu 22.04 LTS+ |
| **RAM** | 2 GB | 4 GB or higher |
| **Disk Space** | 250 MB free space | 1 GB free space (for local cache & DB) |
| **Display** | 1280 x 720 resolution | 1920 x 1080 resolution |

---

## 🔒 Verification & Integrity

Each release asset includes cryptographic SHA256 checksums in the release notes. To verify the integrity of your downloaded package:

**On Linux / macOS:**
```bash
sha256sum <filename>
```

**On Windows (PowerShell):**
```powershell
Get-FileHash <filename> -Algorithm SHA256
```

Compare the computed hash with the hash published in the respective [Release Notes](https://github.com/Mr-Bhardwa7/PharmaBill/releases).

---

## 📄 License & Terms

PharmaBill is proprietary software. All rights reserved.

Copyright (c) 2026 **Animesh Bhardwaj (PharmaBill)**.

Redistribution, reverse engineering, decompilation, unauthorized modification, or mirroring of these packages without written permission is strictly prohibited. See the [LICENSE](LICENSE) file for complete terms.
