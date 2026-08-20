<div align="center">

  # 🌌 ZENITH
  ### *Elevate Your Focus. Reach the Peak of Productivity.*

  <p align="center">
    <img src="https://img.shields.io/badge/Platform-Android_8.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
    <img src="https://img.shields.io/badge/Language-Kotlin_1.9.20-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
    <img src="https://img.shields.io/badge/UI-Jetpack_Compose_Material3-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose" />
    <img src="https://img.shields.io/badge/Backend-Firebase_Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
    <img src="https://img.shields.io/badge/Release-v1.0.0-00E676?style=for-the-badge" alt="Release v1.0.0" />
  </p>

  <p align="center">
    <b>A high-performance, dark-themed focus tracker built with Jetpack Compose, living canvas aura animations, interactive social share cards, and real-time scholar leaderboards.</b>
  </p>

  <br />

  [📱 Download Latest APK](#-download--releases) • [✨ Features](#-key-features) • [📸 Screenshots](#-app-screenshots) • [⚡ Tech Stack](#-tech-stack)

</div>

---

## 🌟 About Zenith

**ZENITH** is a premium, distraction-free study and productivity companion designed for students, competitive programmers, and developers who demand peak deep work. 

Combining living canvas particle visuals with strict single-tap edge-to-edge focus modes, social anime share cards, and real-time global scholar rankings, Zenith turns every study session into an engaging journey toward mastery.

---

## 📸 App Screenshots

<div align="center">

| 🌌 Living Aura Home | 🧘 Edge-to-Edge Focus | 📊 Scholar Profile | 🎴 Anime Share Card | 📱 Custom Notification |
| :---: | :---: | :---: | :---: | :---: |
| <img src="./screenshots/home_screen.png" width="180" alt="Home Screen" /> | <img src="./screenshots/focus_mode.png" width="180" alt="Focus Mode" /> | <img src="./screenshots/profile_screen.png" width="180" alt="Profile Ranks" /> | <img src="./screenshots/share_card.png" width="180" alt="Share Card" /> | <img src="./screenshots/notification_card.png" width="180" alt="Notification Card" /> |

> *Place your screenshots inside the `./screenshots/` directory with the filenames `home_screen.png`, `focus_mode.png`, `profile_screen.png`, `share_card.png`, and `notification_card.png`.*

</div>

---

## ✨ Key Features

### 🌌 1. Living Particle Aura Timer
- **Animated Canvas Particles**: 8 orbiting energy particles and 24 flickering shimmer dots continuously breathe and orbit around the timer display.
- **Tabular Precision**: Ultra-clear `00:00:00` display formatted with zero digit clipping across all screen sizes.

### 🧘 2. Distraction-Free Focus Mode
- **Edge-to-Edge Fullscreen**: Tap anywhere on the Home Screen to enter full-screen Focus Mode.
- **System Bar Hiding**: Suppresses status bars and notification icons to create an uninterrupted deep work environment.
- **Single-Tap Exit**: Exit Focus Mode with a simple tap anywhere on screen.

### 🎴 3. Social Anime Progress Cards
- **Signature Anime Background**: High-resolution anime wallpaper backdrop with solid white official ZENITH logo.
- **Multi-Timeframe Summaries**: Select between **Today (Daily Wrap-Up)**, **This Week (Weekly Summary)**, and **This Month (Monthly Milestone)**.
- **Social Media Ready**: Exported at 4:5 aspect ratio (1080 x 1350 px), optimized for LinkedIn, X/Twitter, Instagram, and WhatsApp.

### 🏆 4. Scholar Ranks & Global Leaderboards
- **Gamified Ranks**: Earn titles from *Initiate* to *Archmage* as your focus hours grow.
- **Real-Time Firebase Sync**: Compete live with scholars around the globe powered by Google Cloud Firestore.

### 📱 5. Custom Notification Shade Card
- **Interactive Controls**: Pause, Resume, and Stop timer sessions directly from your Android notification bar.
- **Lightweight RemoteViews**: Built with custom Android `RemoteViews` featuring the solid white Zenith logo, category badge, and live timer readout.

---

## 📦 Download & Releases

Get the latest production Android build (`.apk`) directly below:

<div align="center">

### 🚀 [Download Zenith v1.0.0 APK](https://github.com/YOUR_GITHUB_USERNAME/Zenith/releases/download/v1.0.0/Zenith-v1.0.0.apk)
*(Build Size: ~18 MB | Target: Android 8.0+ / API 26+)*

</div>

### 📲 How to Install:
1. Click the **[Download Zenith v1.0.0 APK](https://github.com/YOUR_GITHUB_USERNAME/Zenith/releases/download/v1.0.0/Zenith-v1.0.0.apk)** link above on your Android device.
2. Open the downloaded `.apk` file.
3. If prompted, enable **"Install from unknown sources"** in your browser/file manager settings.
4. Tap **Install** and open **ZENITH** to launch your first session!

---

## ⚡ Tech Stack & Architecture

| Layer | Technology Used |
| :--- | :--- |
| **Language** | Kotlin 1.9+ |
| **UI Framework** | Jetpack Compose + Material Design 3 |
| **Architecture** | Clean Architecture + MVVM + Unidirectional Data Flow |
| **Dependency Injection** | Hilt (Dagger) |
| **Async & Data Streams** | Kotlin Coroutines + StateFlow / SharedFlow |
| **Local Storage** | Room Database + Jetpack DataStore |
| **Cloud & Auth** | Firebase Authentication + Cloud Firestore |
| **Foreground Service** | Android 14+ FGS (`specialUse`) + Custom RemoteViews |

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

<div align="center">

Crafted with ❤️ for Deep Work and High Achievement.

</div>
