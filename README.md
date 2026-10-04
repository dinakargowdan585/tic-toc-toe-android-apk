# 🎮 Tic Tac Toe - Android Game

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84.svg?style=flat&logo=android)](https://www.android.com/)
[![UI](https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4.svg?style=flat&logo=jetpackcompose)](https://developer.android.com/jetpack/compose)
[![Language](https://img.shields.io/badge/Language-Kotlin-7F52FF.svg?style=flat&logo=kotlin)](https://kotlinlang.org/)
[![Status](https://img.shields.io/badge/Release-v1.0.0-blue.svg)](https://github.com/dinakargowdan585/tic-toc-toe-android-apk)

A modern, fluid, and beautifully designed **Tic Tac Toe** game built natively for Android using **Jetpack Compose** and **Material 3**. Play against a smart AI or challenge a friend in local pass-and-play multiplayer!

---

## ✨ Features

- 🤖 **Smart AI Opponent**: Play solo against an intelligent AI with selectable difficulty levels.
- 👥 **2-Player Local Mode**: Pass-and-play mode to challenge friends on the same device.
- 🎨 **Modern Jetpack Compose UI**: Built with Material Design 3, smooth animations, and adaptive layouts.
- 🎊 **Victory Confetti & Strike Lines**: Engaging visual feedback with animated strike lines across winning combos and festive confetti explosions upon winning.
- 🔊 **Sound Effects (SFX)**: Immersive audio feedback for moves (X & O), button clicks, undo actions, game draws, and victory fanfares.
- ↩️ **Undo Moves**: Made a wrong move? Revert your last step with the built-in undo feature.
- 📊 **Live Scoreboard**: Keeps track of wins, losses, and draws across sessions.

---

## 🛠️ Tech Stack & Architecture

- **Language:** Kotlin
- **UI Framework:** Jetpack Compose & Material 3
- **Architecture:** MVVM (Model-View-ViewModel) + StateFlow / Coroutines
- **Graphics & Animation:** Canvas drawing (`WinningStrikeLine`, `DrawPlayerMark`), Compose Particle System (`ConfettiParticle`)
- **Audio Engine:** Android SoundPool (`SoundManager`)
- **Persistence:** Local Data Repository

---

## 📥 Download & Installation

You can download and install the pre-built APK directly from this repository:

1. Download [`TicTacToe.apk`](./TicTacToe.apk) from the root of this repository (or from the latest Release).
2. On your Android phone, locate the downloaded file and open it.
3. If prompted, enable **"Install unknown apps"** in your device security settings.
4. Tap **Install** and enjoy playing!

---

## 🕹️ How to Play

1. **Choose Mode:** Select single-player mode (against the AI) or 2-player local mode.
2. **Take Turns:** Player 1 plays as **X**, and Player 2 (or AI) plays as **O**.
3. **Win Condition:** Align 3 matching symbols horizontally, vertically, or diagonally to win the round!
4. **Reset / Next Round:** Start a new round anytime with the reset button while retaining your scores.

---

## 👤 Author

Developed by **[Dinakar Gowda](https://github.com/dinakargowdan585)**  
Email: [dinakargowdan585@gmail.com](mailto:dinakargowdan585@gmail.com)