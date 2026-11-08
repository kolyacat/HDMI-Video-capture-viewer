[README.md](https://github.com/user-attachments/files/34556093/README.md)
# 🎮 PS2 HDMI Screen Capture & Display Adjuster (`PS2-Viewer`)

An open-source, zero-latency web application designed to capture, view, and recalibrate PlayStation 2 video streams from HDMI Capture Cards and PS2-to-HDMI adapters directly inside any modern web browser.
It specifically solves common hardware and software issues when playing PS2 games via Open PS2 Loader (OPL) and GSM (Graphics Synthesizer Mode), such as screen shifts, squished/stretched aspect ratios, black overscan borders, and muffled audio caused by browser noise suppression.

## ✨ Features
* 🎨 **Google Pixel Material You (Monet) Dark UI**
  Modern, clean, and responsive design inspired by Android 14 / Google Pixel Slate UI.

* 🗣️ **Pure Hiragana & English Dual-Language UI**
  Designed with beginner-friendly Hiragana (ひらがな) on top and English on the bottom with clean separator lines.

* 🔊 **Raw Stereo Unprocessed Audio Engine**
  Bypasses browser noise suppression, echo cancellation, and auto-gain control to restore crisp, unmuffled 48kHz stereo sound from game tracks. Includes a live VU audio meter and gain control up to 200%.

* 🖼️ **Aspect Ratio & Anti-Distortion Controls**
  * **4:3 Anti-Distortion:** Preserves original 4:3 aspect ratio without stretching characters.
  * **Crop Black Edges:** Automatically crops out top/side black overscan borders baked into PS2 video signals.
  * **16:9 Fit & Full Stretch:** Expands video to fill your display with strict 16:9 viewport boundaries.

* ⚙️ **GSM OPL Presets & Manual Fine-Tuning**
  * Instant One-Click Presets for **GSM 1080p**, **GSM 480p**, and **Full Stretch**.
  * Manual sliders for **Zoom (Scale)**, **Horizontal Pan (X)**, and **Vertical Pan (Y)** to realign shifted game screens.
  * Picture adjustments: **Brightness**, **Contrast**, and **Color Saturation**.

* 📸 **Built-in Capture & Retro Tools**
  * **PNG Screenshot:** High-resolution screen capture downloaded with timestamp.
  * **Scanline Simulation:** Optional CRT overlay effect for a classic retro gaming experience.

## ⌨️ Keyboard Shortcuts
| Key | Action | 
| ----- | ----- | 
| F | Toggle Fullscreen Mode | 
| S | Take PNG Screenshot | 
| M | Mute / Unmute Audio | 
| R | Reset Screen Position & Scale | 

## 🚀 How to Use

### Method 1: Web Browser (GitHub Pages)
1. Open the live link: `https://kolyacat.github.io/PS2-Viewer/`
2. Connect your **PS2** with a **PS2toHDMI** adapter to your laptop via an **HDMI Video Capture Card**.
3. Select your **Video Input** and **Audio Input** devices from the settings panel.
4. Click **つなぐ / Connect** and enjoy zero-latency PS2 gaming!

### Method 2: Offline / Local Access
1. Clone or download this repository.
2. Double-click `index.html` to open it in Google Chrome, Microsoft Edge, or Brave.
3. Allow Camera & Microphone permissions when prompted by your browser.

## 🛠️ Hardware Setup Recommendation

```
[ PS2 Console ] ---> [ PS2toHDMI Adapter ] ---> [ HDMI Cable ] ---> [ USB Video Capture Card ] ---> [ Laptop USB ]

```

## 📜 License

Distributed under the **MIT License**. Feel free to modify, distribute, or use it for personal gaming setups.
