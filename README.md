<div align="center">
  <img src="assets/logo.png" alt="LumaGrab Logo" width="128" height="128" />

  # LumaGrab
  **Universal Media Downloader & Local FFmpeg Conversion Studio for Windows PC**

  [![Latest Release](https://img.shields.io/github/v/release/muallimun/LumaGrab?color=6366F1&label=Latest%20Release&style=for-the-badge)](https://github.com/muallimun/LumaGrab/releases/latest)
  [![Downloads](https://img.shields.io/github/downloads/muallimun/LumaGrab/total?color=10B981&label=Downloads&style=for-the-badge)](https://github.com/muallimun/LumaGrab/releases)
  [![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(64--bit)-0F172A?style=for-the-badge&logo=windows)](https://github.com/muallimun/LumaGrab/releases/latest)
  [![Privacy](https://img.shields.io/badge/Privacy-Zero%20Ads%20%E2%80%A2%20Zero%20Telemetry-059669?style=for-the-badge)](PRIVACY_POLICY.md)
  [![License](https://img.shields.io/badge/License-Freeware%20(Proprietary)-F59E0B?style=for-the-badge)](LICENSE.txt)

  🌐 **[Official Product Page](https://muallimun.com/LumaGrab/)** • 📦 **[GitHub Releases](https://github.com/muallimun/LumaGrab/releases/latest)** • 🛡️ **[Security & SHA-256](SECURITY.md)** • 🔒 **[Privacy Policy](PRIVACY_POLICY.md)** • 🐛 **[Report an Issue](https://github.com/muallimun/LumaGrab/issues)**

  *Available in 8 Languages: English • Türkçe • العربية • Русский • فارسی • हिन्दी • Français • Deutsch*
</div>

---

## ✨ Overview

**LumaGrab** is a fast, modern, distraction-free desktop media downloader and offline FFmpeg conversion studio developed under the **Muallimun.Net** digital ecosystem. Designed exclusively for **Windows 10 & Windows 11 (64-bit) PCs**, it enables effortless downloading of 8K/4K/1080p videos, full playlists, 320 kbps audio tracks, and multi-language subtitles—with **zero ads, zero telemetry, and no command-line complexity**.

---

## 🚀 Official Download & Security Verification (v1.0.0)

| Edition | Description | Direct Download | Security & VirusTotal |
| :--- | :--- | :--- | :--- |
| **💿 Standard Installer (Recommended)** | Full setup wizard with Start Menu & Desktop shortcuts, `%APPDATA%` isolation, and clean Windows Uninstaller. | **[⬇ LumaGrab_Setup.exe](https://github.com/muallimun/LumaGrab/releases/latest/download/LumaGrab_Setup.exe)** | **[🔍 VirusTotal Report](https://www.virustotal.com/gui/file/724e8344603cffe9cf4ec0af8ac74c752b9376ce247bdcce2de2a0c10a96a822)** |
| **🎒 Portable Edition (Single `.exe`)** | Zero installation required. Run directly from any folder or USB drive with FFmpeg & Deno built in. | **[⬇ LumaGrab_Portable.exe](https://github.com/muallimun/LumaGrab/releases/latest/download/LumaGrab_Portable.exe)** | **[🔍 VirusTotal Report](https://www.virustotal.com/gui/file/0daa781de12aad53466eb0394f8e4c7a5ae924e637290b5150ce6387aa672584)** |

### ⚡ Install via Windows Package Manager (WinGet)
```powershell
winget install Muallimun.LumaGrab
```

### 🔐 Official SHA-256 Checksums (v1.0.0)
```text
LumaGrab_Setup.exe    : 724e8344603cffe9cf4ec0af8ac74c752b9376ce247bdcce2de2a0c10a96a822
LumaGrab_Portable.exe : 0daa781de12aad53466eb0394f8e4c7a5ae924e637290b5150ce6387aa672584
```
> Verify in PowerShell: `Get-FileHash .\LumaGrab_Setup.exe -Algorithm SHA256`

---

## 🖼️ Interface Preview

<div align="center">
  <img src="assets/preview-dark.png" alt="LumaGrab Dark Mode" width="48%" />
  <img src="assets/preview-light.png" alt="LumaGrab Light Mode" width="48%" />
</div>

---

## 🔥 Why LumaGrab? (Key Features)

* **🎯 8K / 4K / 1080p Auto-MP4 Studio:** Inspect real stream resolutions before downloading and automatically merge separate DASH video/audio streams into universally compatible **H.264/MP4** containers.
* **🎵 Studio-Grade Audio Extraction:** Extract crystal-clear **MP3 (320 kbps), M4A, and lossless FLAC** audio with embedded cover art thumbnails and ID3 metadata.
* **📂 Smart Playlist & Batch Queue:** Automatically organizes playlists into dedicated, sequentially numbered subfolders (`01 - ...`, `02 - ...`) and supports multi-URL batch queuing.
* **⚡ Built-in Offline FFmpeg Converter:** Convert local `.webm`, `.mkv`, `.mov`, `.avi`, and `.wav` files on your PC without an internet connection (*Fast Container Remux, Universal H.264, MP3, M4A, WAV*).
* **⏸️ Parallel Queue with Byte-Level Resume:** Download up to 5 streams simultaneously, limit bandwidth (`KB/s`), pause active tasks anytime, and resume from the exact byte offset.
* **💬 Subtitles (CC) & Local Cookie Privacy:** Fetch `.srt` subtitles in multiple languages, optionally embed them into videos, and unlock age-restricted or member-only media using local browser cookies (*Firefox, Chrome, Edge, Brave, or `cookies.txt`*).
* **🌍 Instant 8-Language Switching:** Real-time UI translation across **English, Turkish, Arabic, Russian, Persian, Hindi, French, and German** without restarting, paired with **Dark / Light / System** themes.
* **🔄 Dual Update Architecture (App + Core Engine):** Update the core `yt-dlp` extraction engine independently in seconds whenever video platforms change their algorithms, and receive full LumaGrab application updates via the built-in GitHub Update Center.

---

## 💻 System Requirements

* **Operating System:** Windows 10 (64-bit) or Windows 11 (64-bit) — *Desktop/Laptop PC only*
* **Architecture:** x64 (`amd64`)
* **Dependencies:** **None** *(FFmpeg, FFprobe, Python runtime, and Deno JS solver are pre-bundled inside both editions)*
* **Clean Software Guarantee:** 100% Freeware • Zero Ads • Zero Bundled Adware • Zero Telemetry

---

## 🇹🇷 Türkçe Özet

**LumaGrab**, **Muallimun.Net** çatısı altında yalnızca **Windows 10 / 11 (64-bit) bilgisayarlar** için geliştirilen reklamsız, hızlı ve modern bir masaüstü medya indirici ve yerel format dönüştürme stüdyosudur.
* **4K / 1080p Otomatik MP4 Birleştirme** ve kapak resimli **320 kbps MP3 / M4A / FLAC** ses ayıklama.
* **Oynatma Listesi (Playlist)** videolarını kendi klasörüne sıralı indirme ve **Toplu Bağlantı (Batch URL)** desteği.
* Yerleşik **Çevrimdışı FFmpeg Dönüştürücü**, **Altyazı (.srt) İndirme**, **Pano Bağlantı Algılayıcı** ve **8 Dilde Canlı Arayüz**.
* **🚀 Bağımsız Çekirdek Motor Güncelleyici (`yt-dlp`):** Video platformları algoritmalarını değiştirdiğinde, tüm programı yeniden indirip kurmaya gerek kalmadan Ayarlar sekmesinden yalnızca `yt-dlp` çekirdek motorunu saniyeler içinde güncelleyebilme.
* 🌐 **Resmi Tanıtım ve Kullanım Kılavuzu:** **[https://muallimun.com/LumaGrab/](https://muallimun.com/LumaGrab/)**

---

## 🛡️ Security & Windows SmartScreen Note

Because LumaGrab is distributed as independent freeware without a commercial Extended Validation (EV) hardware certificate, Windows Defender SmartScreen may display an *"Unrecognized app"* prompt on first launch:
1. Verify the file checksum against our [Security Policy](SECURITY.md) and VirusTotal reports above.
2. Click **More info** (*Ek bilgi*) → **Run anyway** (*Yine de çalıştır*).

---

## 📜 Documentation & Legal Notices

* 📄 **[End-User License Agreement (LICENSE.txt)](LICENSE.txt)** — Proprietary Freeware EULA (Free for personal & educational use).
* 🔒 **[Privacy Policy (PRIVACY_POLICY.md)](PRIVACY_POLICY.md)** — Zero telemetry, zero analytics, 100% local processing.
* 🛡️ **[Security Policy (SECURITY.md)](SECURITY.md)** — Official distribution channels, SHA-256 verification, and vulnerability reporting.
* ⚖️ **[Third-Party Open Source Notices (THIRD_PARTY_NOTICES.txt)](THIRD_PARTY_NOTICES.txt)** — Attributions for `yt-dlp`, `FFmpeg`, `Deno`, `CustomTkinter`, and `Pillow`.
* 📋 **[Changelog (CHANGELOG.md)](CHANGELOG.md)** — Version history and release notes.

<div align="center">
  <sub>Copyright © 2026 <b>Muallimun.Net</b> — <a href="https://muallimun.com/LumaGrab/">muallimun.com/LumaGrab</a>. All Rights Reserved.</sub>
</div>