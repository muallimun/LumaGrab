# Privacy Policy for LumaGrab

**Effective Date:** November 10, 2026  
**Last Updated:** November 10, 2026  
**Product:** LumaGrab — Universal Media Downloader & FFmpeg Studio  
**Publisher:** Muallimun.Net (`https://muallimun.com/LumaGrab/`)

---

## 1. Core Privacy Commitment (Zero Data Collection)

**LumaGrab** is engineered as a privacy-first, local-execution desktop application for Windows 10 and Windows 11 (64-bit). **Muallimun.Net does not collect, store, transmit, rent, or sell any personal data, browsing history, downloaded media URLs, or usage metrics.**

---

## 2. Telemetry & Analytics

* **No Telemetry:** LumaGrab contains zero telemetry modules, crash-reporting beacons, or hidden background services.
* **No Analytics:** LumaGrab does not integrate Google Analytics, Sentry, Mixpanel, or any third-party tracking SDKs within the desktop application.
* **No User Profiling:** We do not track which URLs you analyze, what media files you download, your IP address, hardware identifiers, or how often you open the software.

---

## 3. Personal Data & 100% Local Processing

All data generated during your use of LumaGrab remains strictly on your local storage device:

1. **Application Settings (`settings.json`):** Interface language, theme preference, download directory path, concurrency limits, and subtitle preferences are stored locally on your machine.
2. **Download History & Favorites (`library.db`):** Completed download records and bookmarked URLs are stored in a local SQLite database on your computer:
   * **Standard Installer Edition:** Stored under `%APPDATA%\LumaGrab\`.
   * **Portable Edition:** Stored inside the local data directory adjacent to `LumaGrab_Portable.exe`.
3. **Media Conversion:** All video/audio merging and format conversions are executed offline on your CPU/disk via the bundled FFmpeg binary. No media files are ever uploaded to external cloud conversion servers.

You may delete your local history and configuration at any time from within the application UI or by removing the local application data folder.

---

## 4. Browser Cookies & Authentication Privacy

LumaGrab provides an optional **Cookie Source** feature (supporting Firefox, Chrome, Edge, Brave, Opera, Vivaldi, or a user-supplied `cookies.txt` file) to allow users to download age-restricted or member-only streams they are authorized to access.

* **Strictly Local Execution:** When enabled, session cookies are read locally by the underlying `yt-dlp` engine running on your computer strictly to authenticate the HTTP request directly with the target media platform (e.g., YouTube, Vimeo, X, Instagram).
* **Zero Exfiltration:** Your browser cookies, session tokens, and login credentials are **never** transmitted to Muallimun.Net or any intermediary server.

---

## 5. Outbound Network Connections & Third-Party Services

LumaGrab initiates network connections **only** when explicitly triggered by user action:

1. **Target Media Platforms:** When you click *Analyze* or *Download*, LumaGrab connects directly from your IP address to the media URL you provided (via `yt-dlp`). Your interaction with those platforms is governed by their respective privacy policies and terms of service.
2. **Official Application & Engine Updates (GitHub API):**
   * When checking for application updates (or syncing the latest version tag on our website), a standard HTTPS `GET` request is made to `api.github.com/repos/muallimun/LumaGrab/releases/latest`.
   * When you click **Update Core Engine (`yt-dlp`)** in Settings, LumaGrab downloads the latest official release binary directly from GitHub (`github.com/yt-dlp/yt-dlp`).
   * These requests are subject to [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

---

## 6. Official Website (`muallimun.com/LumaGrab/`)

* The official LumaGrab product webpage uses browser `localStorage` solely to remember your preferred page language (`EN` or `TR`) and `sessionStorage` to cache the latest GitHub release version number so as not to exceed GitHub API rate limits.
* The webpage does not use advertising cookies, behavioral trackers, or third-party marketing pixels.

---

## 7. Contact Information

If you have any questions regarding this Privacy Policy or LumaGrab's data practices, please contact us via:

* **GitHub Issues:** [https://github.com/muallimun/LumaGrab/issues](https://github.com/muallimun/LumaGrab/issues)
* **Official Product Portal:** [https://muallimun.com/LumaGrab/](https://muallimun.com/LumaGrab/)
* **Ecosystem Portal:** [https://muallimun.net](https://muallimun.net)