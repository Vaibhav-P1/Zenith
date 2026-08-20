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
    <b>A high-performance, dark-themed focus tracker built with Jetpack Compose, living canvas aura animations, 3-tab visual analytics, interactive social share cards, and real-time scholar leaderboards.</b>
  </p>

  <br />

  [📱 Download Latest APK](#-download--releases) • [✨ Key Features](#-key-features) • [📊 Analytics](#-visual-productivity-analytics) • [📸 Screenshots](#-app-screenshots) • [⚡ Tech Stack](#-tech-stack--architecture)

</div>

---

## 🌟 About Zenith

**ZENITH** is a premium, distraction-free study and productivity companion designed for students, competitive programmers, and developers who demand peak deep work. 

Combining living canvas particle visuals with strict single-tap edge-to-edge focus modes, 3-tab deep work analytics, social anime share cards, and real-time global scholar rankings, Zenith turns every study session into an engaging journey toward mastery.

---

## 📸 App Screenshots

<div align="center">

<img src="https://github.com/user-attachments/assets/0a4f684a-e0e6-41c0-bdb2-be265519bfbe" width="250" alt="Zenith Living Aura Home"/>
<img src="https://github.com/user-attachments/assets/981b909c-98da-4d85-ba6a-82fc1b4c5ab6" width="250" alt="Zenith Subject Selection"/>
<img src="https://github.com/user-attachments/assets/b157c7c1-de8e-402f-bcf0-5ff0a05a1481" width="250" alt="Zenith Fullscreen Focus Mode"/>

<br/><br/>

<img src="https://github.com/user-attachments/assets/0a790d15-f953-43c2-a9a4-408040dff3ea" width="250" alt="Zenith Daily & Weekly Analytics"/>
<img src="https://github.com/user-attachments/assets/7df24f68-4a9f-494a-9131-518a78ebb66b" width="250" alt="Zenith Activity Heatmap"/>
<img src="https://github.com/user-attachments/assets/29ea9757-52db-4d28-90d1-f5879da200cf" width="250" alt="Zenith Scholar Leaderboard"/>

<br/><br/>

<img src="https://github.com/user-attachments/assets/a4b96948-e130-4946-ba1a-40621721598e" width="250" alt="Zenith Profile & Ranks"/>
<img src="https://github.com/user-attachments/assets/1ed30d98-29a2-4a9c-a62e-7c132f4b5a4e" width="250" alt="Zenith Social Anime Share Card"/>
<img src="https://github.com/user-attachments/assets/8e7f2066-ded9-4f69-8826-0a13bd00488e" width="250" alt="Zenith Custom Notification Shade"/>

<br/><br/>

<img src="https://github.com/user-attachments/assets/98da50ee-f10f-4963-a842-01cb5f80413e" width="650" alt="Zenith Overview Deck"/>

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

### 📈 3. Deep Productivity Analytics
- **3-Tab View**: Seamlessly switch between **Daily**, **Weekly**, and **Monthly** visual breakdowns.
- **Subject-by-Subject Insights**: Track focus time allocation across custom subjects (DSA, Dev, OS, CN, DBMS, Aptitude, etc.).
- **Interactive Heatmap & Bar Charts**: Tap any day or heatmap cell to inspect individual session logs and subject percentages.

### 🎴 4. Social Anime Progress Cards
- **Signature Anime Background**: High-resolution anime wallpaper backdrop with solid white official ZENITH logo.
- **Multi-Timeframe Summaries**: Select between **Today (Daily Wrap-Up)**, **This Week (Weekly Summary)**, and **This Month (Monthly Milestone)**.
- **Social Media Ready**: Exported at 4:5 aspect ratio (1080 x 1350 px), optimized for LinkedIn, X/Twitter, Instagram, and WhatsApp.

### 🏆 5. Scholar Ranks & Global Leaderboards
- **Gamified Ranks**: Earn titles from *Initiate* to *Archmage* as your focus hours grow.
- **Real-Time Firebase Sync**: Compete live with scholars around the globe powered by Google Cloud Firestore.

### 📱 6. Custom Notification Shade Card
- **Interactive Controls**: Pause, Resume, and Stop timer sessions directly from your Android notification bar.
- **Lightweight RemoteViews**: Built with custom Android `RemoteViews` featuring the solid white Zenith logo, category badge, and live timer readout.

---

## 📊 Visual Productivity Analytics

Zenith features a dedicated **3-Tab Visual Dashboard** powered by Room SQL queries and reactive Kotlin `StateFlow` streams:

| Analytics Tab | Key Metrics & Visualizations |
| :--- | :--- |
| **Daily View** | **Total Focus Time**, **Sessions Completed**, **Average Session Length**, **Subject Percentage Breakdown Bar**, and a chronological **Completed Session Log** with timestamps. |
| **Weekly View** | **Weekly Total**, **Daily Average Focus Time**, **Best Day Highlight**, and an **Interactive Bar Chart** (tap any bar to view the subject breakdown for that specific day). |
| **Monthly View** | **Monthly Cumulative Hours**, **Active Streak Days**, **GitHub-style Activity Heatmap** with intensity legend, and single-tap date detail inspection. |

---

## 🔧 Database Integrity & Deduplication Fix (v1.0.0)

In version **1.0.0**, Zenith introduced a self-healing database migration and schema constraint to resolve subject duplicate issues:

- **Unique Subject Constraint**: Updated the `Category` Room entity with a `UNIQUE` index on subject `name`.
- **Automatic Migration (`MIGRATION_2_3`)**: Automatically cleans up legacy duplicate subject buttons on app update without affecting past study session logs.
- **Concurrent Seeding Guard**: Hardened default subject initialization to prevent race conditions on initial app launch.

---

## 📦 Download & Releases

Get the latest production Android build (`.apk`) directly below:

<div align="center">

### 🚀 [Download Zenith v1.0.0 APK](https://github.com/YOUR_GITHUB_USERNAME/Zenith/releases/download/v1.0.0/Zenith-v1.0.0.apk)
*(Build Size: ~26 MB | Target: Android 8.0+ / API 26+)*

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
| **Local Storage** | Room Database (v3 Migration) + Jetpack DataStore |
| **Cloud & Auth** | Firebase Authentication + Cloud Firestore |
| **Foreground Service** | Android 14+ FGS (`specialUse`) + Custom RemoteViews |

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

<div align="center">

Crafted with ❤️ for Deep Work and High Achievement.

</div>
