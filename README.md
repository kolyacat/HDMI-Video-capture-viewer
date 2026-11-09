[README.md](https://github.com/user-attachments/files/34560656/README.md)
# 📺 HDMI Video Capture Viewer

A universal, zero-latency web application designed to capture, view, and recalibrate HDMI video and audio streams from USB Capture Cards directly inside any modern web browser.

It solves common capture hardware issues such as squished or stretched aspect ratios, black overscan borders, and muffled/distorted audio caused by browser noise suppression filters.

## ✨ Key Features

* 🎨 **Google Pixel Material You (Monet) Dark Theme**
  Clean, modern UI inspired by Android 14 / Google Pixel Slate styling, complete with custom pill controls and rounded containers.

* 🌐 **Multi-Language Support (i18n)**
  Switch seamlessly between **🇬🇧 English**, **🇮🇩 Bahasa Indonesia**, and **🇮🇩 Bahasa Sunda**. Language preferences are automatically saved in `localStorage`.

* 🔊 **Raw Stereo Unprocessed Audio Engine**
  Bypasses browser noise suppression, echo cancellation, and auto-gain control to capture clean 48kHz stereo sound. Includes a live VU audio meter and Volume Gain Boost up to 200%.

* 🖼️ **Strict 16:9 Viewport & Anti-Distortion Aspect Controls**

  * **4:3 Native:** Ideal for legacy 4:3 video sources without horizontal stretching.

  * **Crop Black Edges:** Automatically crops out top and side overscan lines.

  * **16:9 Fit:** Standard widescreen fitting inside the 16:9 container.

  * **Full Stretch:** Stretches the video stream to fill the entire container.

* ⚙️ **Manual Fine-Tuning & Quick Presets**

  * Quick 1-click display presets: **Fit 1080p HD**, **Fit 480p SD**, and **Reset Default**.

  * Precise sliders for **Zoom (Scale)**, **Horizontal Pan (X)**, and **Vertical Pan (Y)**.

  * Picture adjustments: **Brightness**, **Contrast**, and **Color Saturation**.

* 📸 **Built-in Capture & Retro Tools**

  * **PNG Screenshot:** Save crisp, high-resolution snapshots with timestamps.

  * **Scanlines Simulation:** Toggleable CRT overlay filter for classic display aesthetics.

## ⌨️ Keyboard Shortcuts

| Key | Action | 
| ----- | ----- | 
| F | Toggle Fullscreen Mode | 
| S | Take PNG Screenshot | 
| M | Mute / Unmute Audio | 
| R | Reset Position, Scale & Aspect | 

## 🚀 How to Use

### Method 1: Web Browser (GitHub Pages)

1. Open the live link: `https://kolyacat.github.io/PS2-Viewer/` *(or your repository URL)*.

2. Plug your **HDMI Video Capture Card** into your laptop/PC USB port.

3. Select your **Video Input Device** and **Audio Input Device** from the settings menu.

4. Click **Connect Stream** to view your video feed instantly!

### Method 2: Local File Access

1. Clone or download this repository.

2. Double-click `index.html` to open it in Google Chrome, Microsoft Edge, or Brave.

3. Grant Camera & Microphone permissions when prompted by the browser.

## 🛠️ Hardware Setup Recommendation

```
[ Video Source / Console / Camera ] ---> [ HDMI Cable ] ---> [ USB Video Capture Card ] ---> [ PC / Laptop / Mobile (OTG) ]

```

## 📜 License

Distributed under the **MIT License**. Free to use, modify, and share for personal setups or streaming projects.
