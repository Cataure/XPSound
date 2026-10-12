# XPSound 🎧

**XPSound** is a retro offline music player for Android inspired by the golden era of 90s audio software and classic desktop players like Winamp.

Built specifically for users who store their music locally, XPSound features intelligent audio scanning to filter out video editing clips, sound effects, and voice notes—leaving only your actual music library.

---

## ✨ Key Features

* **Authentic Retro Aesthetic:** Nostalgic Windows 98 / Winamp-inspired UI with physical 3D beveled borders, monospace typography, and analog cassette click sound effects on button press.
* **Persistent Background Playback:** Powered by modern **AndroidX Media3 (ExoPlayer & MediaSessionService)**, ensuring uninterrupted playback when your screen is locked or the app is minimized.
* **Lock Screen & Notification Controls:** Native system media notification card with full transport controls (Play, Pause, Previous, Next) and live track metadata.
* **Smart Audio Filtering:** Automatically filters out voice recordings, WhatsApp audio notes, and short audio clips (< 45 seconds) used in video editing workflows.
* **Playlists & Liked Songs:** Create custom playlists with full emoji support, manage favorites (*Liked Songs*), and sort tracks by title, artist, or duration—fully backed by a local **Room SQLite database**.
* **Oscilloscope Waveform Display:** Central LCD screen featuring an animated green frequency wave accompanying playback.
* **Always-Available Search:** Fixed top search bar for instant real-time filtering across your entire music collection.

---

## 🛠️ Tech Stack

* **Language:** Kotlin
* **UI Framework:** Jetpack Compose (Material 3 with custom retro design tokens)
* **Audio Engine:** AndroidX Media3 (ExoPlayer, MediaSession)
* **Local Persistence:** Room Database (SQLite) with KSP
* **UI Sound FX & Haptics:** SoundPool & Android Haptic Feedback
* **Device Compatibility:** Android 7.0 (API 24) and above — Full support for both smartphones and tablets

---

## 📲 Installation

To install the application directly onto any Android device:

1. Download the latest **`XPSound.apk`** from the project releases or shared build folder.
2. Open the `.apk` file on your Android device and tap **Install** (allow installation from this source if prompted).
3. Grant local audio permissions on first launch to allow the app to scan your device's music files.

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
