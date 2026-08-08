# Locus

A Chrome extension for true 3D spatial audio. Position sounds in space with binaural HRTF, draw occluding geometry, animate movement with macros, shape tone with a 10-band EQ, and measure real rooms — all in the browser.

Runs on any device that can run Chrome. Headphones recommended for the full spatial effect; laptop-speaker mode with crosstalk cancellation is also available.

> v1.5currently published on the Chrome Web Store.

---

## Features (v1.5)

- **3D Cube Panner** — Interactive arcball cube. Snap to a face to lock axes and drag sources precisely in X/Y/Z.
- **Binaural HRTF** — Web Audio HRTF panning so sounds appear to come from real directions (including height).
- **Motion Macros** — Record 3D movement paths and assign them to any track (sweeps, orbits, lifts, loops).
- **Drawable Spaces** — Draw walls and solid objects on the cube faces. They occlude and muffle sound in real time. Save spaces, reuse objects from a library, and switch the active space from the Studio sidebar.
- **Room Acoustics** — Large library of convolution reverb presets (booths, halls, cathedrals, plates, springs, outdoor, character spaces, etc.) plus adjustable wet/dry mix, air absorption, presence, and D/R sharpness.
- **Room Scanner** — Play a sweep through your speakers, capture with the mic, and turn the measured decay into a custom reverb preset that behaves like the built-ins.
- **10-band ISO Graphic EQ** — Per-track and master bus. Built-in Tweeter / Woofer / Subs presets; save your own custom curves. Bypass and reset per target.
- **Multi-Listener** — Two independent listeners, each with its own position, orientation, and output device. Useful for two people on separate headsets.
- **Output modes** — Headphones (plain HRTF), Laptop Speakers (HRTF + crosstalk cancellation with distance calibration), or Multi-Listener.
- **Sources** — Upload files (MP3, WAV, OGG, FLAC, AAC, M4A…), live microphone, or system/tab audio.
- **Transport & Export** — Play all / Stop / Record the full binaural mix to WAV or WebM.
- **UI** — True glass interface, dark/light themes, accent color presets + custom picker.

---

## Quick start

1. Go to **Studio** → **+ ADD** and choose a source (file, mic, or system audio).
2. Rotate the cube until a face snaps (badge shows active axes).
3. Drag a track dot to place the sound in 3D space.
4. Press **▶ PLAY ALL** and wear headphones.
5. Optionally assign a **Macro**, pick a **Space**, or open **EQ** / **Environment**.
6. Press **⏺ REC** to capture and export the mix.

---

## Install (unpacked)

1. Download / clone this repo (or the `1.5` folder).
2. Open `chrome://extensions`, enable **Developer mode**.
3. Click **Load unpacked** and select the extension folder (the one containing `manifest.json`).
4. Click the extension icon to open Spatial Audio Studio.

---

## Notes

- Spatial effect is designed for headphones. Laptop-speaker mode uses crosstalk cancellation and a distance calibration slider.
- Room scanning needs microphone permission and a quiet environment; it measures decay (not speaker tone colouration).
- Custom rooms, spaces, macros, EQ presets, and settings are stored in local storage on the device.

---

## Contact

Questions? You can get my email from my YouTube: [@usbheadphones2](https://www.youtube.com/@usbheadphones2)
