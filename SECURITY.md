# Security Policy & Verification Guide

**Project:** LumaGrab — Universal Media Downloader & FFmpeg Studio  
**Publisher:** Muallimun.Net (`https://muallimun.com/LumaGrab/`)

---

## 1. Supported Versions

Only the latest stable release of **LumaGrab** for Windows 10 & Windows 11 (64-bit) receives active security updates and core extraction engine updates.

| Version | Platform | Supported |
| :--- | :--- | :---: |
| **v1.0.x (Latest)** | Windows 10 / 11 (64-bit x64) | ✅ Yes |
| Pre-release / Unofficial builds | Any | ❌ No |

---

## 2. Official Distribution Channels

To protect yourself against tampered binaries, trojans, or bundled adware, download **LumaGrab** **exclusively** from the following official sources:

1. **Official GitHub Releases:** [https://github.com/muallimun/LumaGrab/releases](https://github.com/muallimun/LumaGrab/releases)
2. **Official Product Website:** [https://muallimun.com/LumaGrab/](https://muallimun.com/LumaGrab/) *(Direct links point to `github.com/muallimun/LumaGrab/releases`)*
3. **Microsoft WinGet Package Manager:** `winget install Muallimun.LumaGrab`
4. **Verified Software Directories:** Softpedia, FossHub, SourceForge, and MajorGeeks listings that distribute unmodified binaries matching the cryptographic SHA-256 hashes below.

> ⚠️ **Warning:** Never download LumaGrab from unofficial crack websites, torrent trackers, or third-party installers that wrap our executable in proprietary download managers.

---

## 3. Cryptographic File Verification (v1.0.0)

Every official release of LumaGrab is verified using **SHA-256** checksums and scanned via **VirusTotal** prior to release.

### 📦 Official v1.0.0 Binaries & Checksums

| Package | File Name | SHA-256 Checksum | VirusTotal Verification |
| :--- | :--- | :--- | :--- |
| **Standard Installer** | `LumaGrab_Setup.exe` | `724e8344603cffe9cf4ec0af8ac74c752b9376ce247bdcce2de2a0c10a96a822` | [View VirusTotal Report](https://www.virustotal.com/gui/file/724e8344603cffe9cf4ec0af8ac74c752b9376ce247bdcce2de2a0c10a96a822) |
| **Portable Edition** | `LumaGrab_Portable.exe` | `0daa781de12aad53466eb0394f8e4c7a5ae924e637290b5150ce6387aa672584` | [View VirusTotal Report](https://www.virustotal.com/gui/file/0daa781de12aad53466eb0394f8e4c7a5ae924e637290b5150ce6387aa672584) |

### 🔍 How to Verify SHA-256 on Windows

Open **Windows PowerShell** or **Command Prompt** in your `Downloads` folder and run:

**PowerShell:**
```powershell
Get-FileHash .\LumaGrab_Setup.exe -Algorithm SHA256
Get-FileHash .\LumaGrab_Portable.exe -Algorithm SHA256
```

**Command Prompt (CMD):**
```cmd
certutil -hashfile LumaGrab_Setup.exe SHA256
certutil -hashfile LumaGrab_Portable.exe SHA256
```

If the resulting hash does not match the values listed above (or in the corresponding GitHub Release notes), **delete the file immediately** and report the source to us.

---

## 4. Note on Windows SmartScreen & Antivirus Heuristics

* **Windows Defender SmartScreen:** Because LumaGrab is distributed as independent freeware without a commercial Extended Validation (EV) hardware certificate, Windows SmartScreen may display an *"Unrecognized app"* prompt when launching a newly released build. Verify the SHA-256 hash above, then click **More info → Run anyway**.
* **PyInstaller Heuristic False Positives:** LumaGrab is built with Python and packaged via PyInstaller (`LumaGrab.spec`) and UPX/Inno Setup (`installer.iss`). Occasionally, 1–2 generic antivirus engines on VirusTotal flag self-extracting PyInstaller bootloaders as heuristic false positives. Always rely on the official SHA-256 checksums above to confirm binary authenticity.

---

## 5. Reporting a Security Vulnerability

We take security vulnerabilities seriously. If you discover a security issue in LumaGrab, its update mechanism, or its local file handling:

1. **Private Reporting (Preferred):** Please use GitHub's **Report a vulnerability** (Private Security Advisory) feature under the [Security tab](https://github.com/muallimun/LumaGrab/security) of this repository, or contact the maintainer through [muallimun.net](https://muallimun.net).
2. **Issue Tracker (Non-Exploitable Bugs):** For general security hardening suggestions that do not expose active end-user exploits, open a report on [GitHub Issues](https://github.com/muallimun/LumaGrab/issues) with the `[Security]` prefix.

### Response Timeline
* **Initial Acknowledgment:** Within **48 hours**.
* **Triage & Verification:** Within **5 business days**.
* **Patch Release & Advisory:** Critical vulnerabilities are patched and published via GitHub Releases as top priority.