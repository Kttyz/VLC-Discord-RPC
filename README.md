# VLC-Discord-RPC
A RPC plugin for VLC Media player to discord!


# VLC Discord Rich Presence (RPC) 🎵

A lightweight Python script that syncs your **VLC Media Player** activity directly to your **Discord Rich Presence** profile in real-time. It features a system tray icon control menu and handles active playback and idle states seamlessly.

---

## Features
* **Real-Time Syncing:** Displays track title, artist, and album.
* **Smart Timers:** Uses Discord's native countdown and elapsed timers for smooth progress tracking.
* **Idle States:** Automatically switches to an idle custom status ("Nothing playing! 🐈‍⬛") with a custom GIF when VLC is paused or stopped.
* **System Tray Integration:** Runs silently in the background with a system tray icon and a quick quit option.

---

## Requirements

* **Python 3.x** installed on Windows.
* **VLC Media Player** with the Web Interface enabled.

### Required Python Packages
Run the command in your powershell to install the dependencies:
---
pip install pypresence requests pystray Pillow
