# Changelog

All notable changes, security verifications, and release milestones for **LumaGrab** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0] - 2026-11-10

### 🎉 Initial Public Release (Stable)

First official production release of **LumaGrab — Universal Media Downloader & Local FFmpeg Studio** for Windows 10 and Windows 11 (64-bit) desktop PCs.

### ✨ Added
* **Universal Media Extraction Engine:** Powered by `yt-dlp` and embedded `Deno` JavaScript signature solver, supporting single videos, audio tracks, playlists, and batch URL lists across hundreds of platforms.
* **High-Resolution Auto-MP4 Merging:** Stream analyzer for **8K, 4K (2160p), 2K (1440p), and 1080p Full HD** streams with automatic lossless container merging into universal `H.264 / MP4` via embedded FFmpeg.
* **Studio Audio Extractor:** Direct extraction to **MP3 (320 kbps), M4A, and lossless FLAC** with automatic cover art thumbnail and ID3 metadata embedding.
* **Smart Playlist & Batch Engine:** Sequential numbering (`01 - ...`, `02 - ...`) inside dedicated playlist subfolders, including fallback parsing for restricted and kids-designated playlists, plus multi-line **Batch URL Add** modal.
* **Parallel Download Queue with Byte-Level Resume:** Configurable simultaneous download slots (`1–5` parallel tasks), custom speed limiter (`KB/s`), pause/resume from exact byte offset (`.part` preservation), and queue filters (*Clear Done, Clear Failed, Clear All*).
* **Offline Local FFmpeg Converter Studio:** Dedicated **Convert** tab to transform local `.webm`, `.mkv`, `.mov`, `.avi`, and audio files offline using 5 curated presets (*MP4 Fast Container Remux, MP4 Universal H.264+AAC, MP3 320 kbps, M4A 256 kbps, and Lossless Studio WAV*).
* **Subtitles (CC) & Browser Cookie Integration:** Multi-language `.srt` subtitle downloading, optional soft-subtitle video embedding, and local browser session cookie reader (*Firefox, Chrome, Edge, Brave, Opera, Vivaldi, or `cookies.txt`*) for age-restricted or member-only media.
* **Real-Time 8-Language Localization:** Instant interface switching without restarting across **English (`en`), Turkish (`tr`), Arabic (`ar`), Russian (`ru`), Persian (`fa`), Hindi (`hi`), French (`fr`), and German (`de`)**.
* **Adaptive Modern UI:** Built with CustomTkinter featuring **Dark, Light, and System** theme modes, live clipboard URL monitor banner, Favorites (`★ Fav`) manager, and SQLite-backed **Library & History** search panel.
* **Dual Update Architecture:**
  * Built-in **GitHub Releases Update Center** for full application upgrades.
  * Independent 1-click **Core Engine (`yt-dlp`) Updater** in Settings to keep extraction algorithms current without reinstalling LumaGrab.
* **Dual Distribution Editions:**
  * `LumaGrab_Setup.exe`: Standard Inno Setup x64 installer with Desktop/Start Menu shortcuts, single-instance mutex protection, `%APPDATA%` user isolation, and clean Windows Uninstaller.
  * `LumaGrab_Portable.exe`: Self-contained single-file portable executable with embedded FFmpeg and Deno, storing user data locally alongside the executable.

### 🛡️ Security & Checksums (v1.0.0)
* **`LumaGrab_Setup.exe` (SHA-256):** `724e8344603cffe9cf4ec0af8ac74c752b9376ce247bdcce2de2a0c10a96a822` — [VirusTotal Report](https://www.virustotal.com/gui/file/724e8344603cffe9cf4ec0af8ac74c752b9376ce247bdcce2de2a0c10a96a822)
* **`LumaGrab_Portable.exe` (SHA-256):** `0daa781de12aad53466eb0394f8e4c7a5ae924e637290b5150ce6387aa672584` — [VirusTotal Report](https://www.virustotal.com/gui/file/0daa781de12aad53466eb0394f8e4c7a5ae924e637290b5150ce6387aa672584)