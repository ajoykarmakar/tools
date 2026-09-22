<div align="center">

# Clean Launcher for Android TV & Google TV 🚀

### *The Ultra-Fast, Bloat-Free ~1.1MB TV Home Screen Replacement*

[![Release](https://img.shields.io/badge/Release-v1.0.0-34a853.svg?style=for-the-badge&logo=android)](https://github.com/ajoykarmakar/tools/raw/refs/heads/main/releases/clean-launcher-v1.0.0.apk)
[![APK Size](https://img.shields.io/badge/Size-~1.1MB-38bdf8.svg?style=for-the-badge)](https://github.com/ajoykarmakar/tools/raw/refs/heads/main/releases/clean-launcher-v1.0.0.apk)
[![FPS](https://img.shields.io/badge/Focus-60fps%20GPU-4ade80.svg?style=for-the-badge)](#-hardware-performance--engineering)
[![Ad-Free](https://img.shields.io/badge/Ads-Zero%20Bloat-purple.svg?style=for-the-badge)](#-privacy-first--transparent-permissions)
[![Website](https://img.shields.io/badge/Live-Demo%20Page-emerald.svg?style=for-the-badge)](https://ajoykarmakar.github.io/tools/index.html)

<p align="center">
  <b>Tired of laggy UI, sponsored rows, and banner ads taking over your smart TV?</b><br>
  Clean Launcher strips away 60MB+ of background telemetry and sponsored renderers in favor of an instantaneous, lightweight, and hardware-accelerated interface.
</p>

[📥 Download Latest APK (v1.0.0)](https://github.com/ajoykarmakar/tools/raw/refs/heads/main/releases/clean-launcher-v1.0.0.apk) • [🌐 Live TV Web Emulator](https://ajoykarmakar.github.io/tools/index.html) • [📖 Sideload Guide](#-quick-sideload-walkthrough)

---

</div>

## 📺 Authentic TV Interface

Designed with standard native Android Views for zero-stutter D-pad navigation:

| Default TV View (Unsplash Sunset Wallpaper) | Solid Color Mode (Zero GPU Overdraw) |
| :---: | :---: |
| <img src="https://github.com/ajoykarmakar/tools/blob/main/UI/4.png?raw=true" alt="Clean Launcher Sunset Wallpaper" width="100%"/> | <img src="https://github.com/ajoykarmakar/tools/blob/main/UI/3.png?raw=true" alt="Clean Launcher Solid Mode" width="100%"/> |

| Personalization Hub (Selection Styles & Unsplash) | Network & Internet Slide-out Drawer |
| :---: | :---: |
| <img src="https://github.com/ajoykarmakar/tools/blob/main/UI/1.png?raw=true" alt="Personalize Launcher Hub" width="100%"/> | <img src="https://github.com/ajoykarmakar/tools/blob/main/UI/2.png?raw=true" alt="Network and Internet Drawer" width="100%"/> |

<div align="center">
  <br>
  <img src="https://github.com/ajoykarmakar/tools/blob/main/UI/5.png?raw=true" alt="Clean Launcher Full Showcase" width="90%"/>
  <p><i>Clean Launcher in action on Android TV & Google TV</i></p>
</div>

---

## ⚡ Key Highlights

* **Ultralight ~1.1MB APK:** Zero third-party design framework bloat. Built directly on native Android SDK primitives so it launches instantly.
* **Instant Return via AppCache:** Eliminates the notorious 1–3 second freeze when exiting streaming apps by bypassing heavy `PackageManager` scans on return trips.
* **60fps GPU `.withLayer()` Texture Baking:** Navigating with your TV remote renders focus transitions smoothly on hardware layers without triggering expensive layout passes.
* **Local 7-Day Usage Sorting:** Automatically organizes your favorite channels and streaming services to the front using Android's native `UsageStatsManager`.
* **Native Live TV Tuner Injection:** Direct scanning via `TvContract` and fallback support for 15+ TV OEM packages (Xiaomi, Sony Bravia, TCL, Samsung, Airtel, etc.) to expose your antenna/cable tile directly in the grid.
* **Dynamic Header Pill & Clock:** Real-time Wi-Fi SSID and Ethernet reachability tracking (🟢 Connected, 🟠 No Internet, 🔴 Offline) paired with a clean 12/24-hour auto-updating date and time readout.

---

## 🎨 Personalization & Storage Guard

Clean Launcher puts visual appeal and device storage on equal footing:

* **Surprise 1080p Landscape Photography:** Fetches curated scenery directly from the Unsplash API.
* **Strict Single-Image Retention Policy:** Every newly downloaded wallpaper completely overwrites the prior cached file. Wallpaper cache never exceeds 1–2MB of internal storage.
* **Debounced API Fetching:** Built-in 3-second cooldown button debounce protects your connection from accidental click storms.
* **Solid Color Battery/GPU Mode:** Destroys background image texture layers entirely to avoid GPU overdraw on entry-level 1GB/2GB sticks.
* **Custom Selection Highlights:** Switch between **Border Outline** (crisp high-contrast focus) and **Classic Zoom** (smooth 10% icon enlargement).

---

## 🛡️ Privacy-First & Transparent Permissions

Everything remains on your TV. No telemetry, no remote ad-servers, no analytics collectors.

| Permission | Purpose | Where Data Goes |
| :--- | :--- | :--- |
| **Default Launcher** | Sets Clean Launcher as your primary home screen. | Stays on device. |
| **Usage Stats** | Sorts your most-used apps to the front based on recent 7-day usage. | Calculated strictly in local memory. |
| **Location Access** | Required by Android OS to query and display your active Wi-Fi SSID name. | Never broadcasted or stored. |

> **Safe Exit Guarantee:** Changing your mind is effortless. Clean Launcher features a dedicated "Exit Launcher" option that routes you straight to Android System Settings to revert back to your factory launcher at any time.

---

## 📥 Quick Sideload Walkthrough

Sideload the APK onto your television or streaming box in less than 3 minutes:

### Option A: Downloader App (Fastest)
1. Install **Downloader by AFTVnews** from the TV Google Play Store.
2. Open Downloader and enter the direct APK URL:
 https://github.com/ajoykarmakar/tools/raw/refs/heads/main/releases/clean-launcher-v1.0.0.apk
