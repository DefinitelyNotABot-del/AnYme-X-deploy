# AnYme X — Desktop Anime Player for Windows

> High-performance, ad-free desktop anime streaming experience built with SvelteKit & Tauri v2.

---

## 🚀 Features

- **Blazing Fast Playback**: Intelligent sliding-window segment prefetcher and live playhead prioritizer for zero buffering.
- **Zero Ads & Zero Popups**: Direct stream resolution with built-in ad and redirect blocking.
- **MyAnimeList Synchronization**: Real-time progress updates, episode count tracking, and watch list management.
- **Auto-Skip & AniSkip Support**: Seamlessly skip intros and outros automatically or with dedicated one-click controls.
- **Smart Segment Caching**: Tiered SSD segment caching for smooth, uninterrupted playback even on unstable connections.
- **Clean Teardown & Uninstaller**: Built-in deep uninstaller completely wipes all application files, caches, and shortcuts with zero residue.

---

## 📥 Downloads & Installation

### Option 1: Windows Setup Installer (Recommended)
Download and run the installer:
- **[AnYme-X-Setup.exe](./AnYme-X-Setup.exe)** (`~10.5 MB`, x64 NSIS)

### Option 2: Windows MSI Package
- **[AnYme-X-Setup.msi](./AnYme-X-Setup.msi)** (`~13.3 MB`, x64 MSI)

---

## 💻 System Requirements

- **OS**: Windows 10 (64-bit) / Windows 11 (64-bit)
- **Runtime**: Microsoft Edge WebView2 (pre-installed on Windows 10/11)
- **RAM**: 2 GB minimum (4 GB recommended)
- **Disk Space**: ~150 MB free space

---

## 🗑️ Clean Uninstallation

To uninstall AnYme X:
1. Open Windows **Settings** > **Apps** > **Installed apps** (or **Control Panel** > **Programs and Features**).
2. Select **AnYme X** and click **Uninstall**.

The uninstaller automatically removes:
- All application files and binaries
- All cached video segments and logs in `%LOCALAPPDATA%\AnYme X`
- Web cache and browser profile databases in `%LOCALAPPDATA%\com.anyme.app`
- Protocol association registry keys and desktop/start menu shortcuts
Leaving strictly zero residue on your system.
