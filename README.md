# Constellation-Windows
# BY - NIFTO(A.K.A - UTKARSH CHANDRA)

# Constellation Lyrics for Windows

A lightweight, click-through desktop overlay for **Windows 10 & Windows 11** that turns your currently playing music into an animated **constellation of glowing stars and connecting beams**, lighting up word-by-word in sync with your track.

---

## Features
* **Word-by-Word Constellation Animation:** Every sung word becomes a drifting star node connected by luminous beams that illuminate in real time.
* **Works With Any Windows Player:** Connects directly to Windows Media Controls (`SMTC`)—supports **Spotify (Free & Premium)**, Apple Music, YouTube in browsers, and local media players with zero account logins.
* **100% Click-Through Overlay:** Floats smoothly over your desktop wallpaper and apps without blocking mouse clicks.
* **Live Visual Settings (`F7`):** Customize star colors (6 presets + full RGB color picker), vertical screen position, font size, and sync timing on the fly.
* **System Tray Integration:** Runs quietly in the background next to your Windows clock and saves your settings automatically.

---

## Download & Installation

1. Go to the **[Releases](../../releases)** page on the right side of this repository.
2. Download **`Constellation_Setup.exe`** under the latest release.
3. Run the installer and follow the setup wizard.
   > **Note on Windows SmartScreen:** Because this is a free indie app without a paid corporate certificate, Windows may show *"Windows protected your PC / Unknown Publisher"*. Click **More info** → **Run anyway** to proceed with installation.

---

## 🎮 Controls & Shortcuts

| Action | Shortcut / Control |
| :--- | :--- |
| **Open Visual Settings** | Press **`F7`** or click the **Star icon** in your Windows System Tray |
| **Sync Lyrics Earlier (-0.5s)** | Press **`[`** |
| **Sync Lyrics Later (+0.5s)** | Press **`]`** |
| **Quit Overlay** | Right-click the System Tray icon → **Quit Constellation** |

---

## 🛠️ Custom Local Lyrics (`.lrc` Support)
Want to use your own custom-timed lyrics for a specific song? Drop a standard `.lrc` file named `<Song Title>.lrc` into the installation folder, and the overlay will automatically prioritize your local timestamps.

---

## 💻 Built With
* **Python** & **pywebview** (Edge WebView2 transparent overlay)
* **HTML5 Canvas** (Real-time particle & constellation rendering)
* **Windows Runtime (`winrt`)** (Native Windows media session & timeline sync)
* **Tkinter & pystray** (Native settings panel & system tray integration)
