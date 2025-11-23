# Carbon Player 📺

A lightweight, high-performance IPTV player for Windows built with Python. 

Unlike standard IPTV apps that use heavy web engines, Carbon Player integrates directly with **MPC-HC** to provide hardware-accelerated playback, 4K support, and 0% CPU usage.

## ✨ Features

* **⚡ Zero Lag:** Optimized for speed using an external video engine.
* **🌑 Dark Mode:** Modern, clean interface that is easy on the eyes.
* **🔍 Instant Search:** Fast filtering for Channels, Movies, and Series within categories.
* **🚀 Hardware Acceleration:** Plays 4K/HDR content smoothly using your GPU.
* **📂 Playlist Management:** Easy Xtream Codes login support.

## 📥 Download

[**Download Carbon Player v1.0 (EXE)**](https://github.com/YOUR_USERNAME/Carbon-Player/releases)

*No installation required. Portable Windows App.*

## 🛡️ Installation Note (Windows SmartScreen)

When you launch `CarbonPlayer.exe` for the first time, you might see a blue window saying **"Windows protected your PC"**.

This happens because I am an independent developer and I have not paid for a Microsoft Digital Code Signing Certificate (which costs hundreds of dollars a year).

**To run the app:**
1. Click **"More Info"**.
2. Click **"Run Anyway"**.

*The application is 100% open source and safe. You can review the code in this repository yourself.*

## 🛠️ Requirements & Setup

To ensure video plays correctly, you must have the appropriate codecs installed:

1.  Download and Install **[K-Lite Codec Pack (Standard)](https://codecguide.com/download_kl.htm)**.
2.  Open **Carbon Player**.
3.  Go to **Settings** -> **Choose Media Player**.
4.  Select `mpc-hc64.exe` (Usually located in `C:\Program Files (x86)\K-Lite Codec Pack\MPC-HC\`).

## 👨‍💻 For Developers

If you want to run the source code instead of the EXE:

1.  Clone the repository.
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Run the app:
    ```bash
    python main.py
    ```

## ⚠️ Disclaimer

**This is a software project only.** * I do **not** sell IPTV subscriptions.
* I do **not** provide any video content.
* This application is a media player designed to play content you already legally own.

---
*Built by SaMubarakk.*
