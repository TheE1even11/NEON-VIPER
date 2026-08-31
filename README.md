# ⚡ NEON VIPER // OVERDRIVE

<p align="center">
  <a href="https://thee1even11.github.io/NEON-VIPER-OVERDRIVE/"><img src="https://img.shields.io/badge/Version-1.0-00f3ff?style=for-the-badge" alt="Version 1.0"></a>
  <img src="https://img.shields.io/badge/License-GPL_3.0-ff0055?style=for-the-badge" alt="License GPL-3.0">
  <img src="https://img.shields.io/badge/Zero-Dependencies-00ff66?style=for-the-badge" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-ffe600?style=for-the-badge" alt="Platform">
  <a href="https://thee1even11.github.io/NEON-VIPER-OVERDRIVE/"><img src="https://img.shields.io/badge/Play%20Online-GitHub%20Pages-9d00ff?style=for-the-badge" alt="Play Live"></a>
</p>

<p align="center">
  <b>Neon Viper: Overdrive</b> is a fast-paced, arcade-style snake remix built with pure HTML5 Canvas and the Web Audio API. Featuring dynamic combo systems, overdrive boost mechanics, procedural synth sound design, and rich particle feedback.
</p>

---

## 🎮 Play Live
Play the game instantly in your web browser:  
👉 **[https://thee1even11.github.io/NEON-VIPER-OVERDRIVE/](https://thee1even11.github.io/NEON-VIPER-OVERDRIVE/)**

---

## 🕹️ Controls

### 💻 Desktop
| Key | Action |
| :--- | :--- |
| **W, A, S, D** or **Arrow Keys** | Steer Viper |
| **SPACE** or **SHIFT** *(Hold)* | **Hyper Boost** (Double speed & multiplier) |
| **P** or **ESC** | Pause / Resume |
| **R** | Instant Restart |

### 📱 Mobile & Touch
- **Virtual D-Pad:** On-screen directional buttons (bottom-left).
- **Boost Button:** Hold the glowing blue trigger (bottom-right) to engage Overdrive.
- **Swipe Gestures:** Swipe anywhere on the screen for swift directional changes.

---

## 💎 Core Mechanics & Power-ups

- 🔵 **Cyan Orb (Standard Food):** Extends viper length, refills boost gauge, and builds your combo meter.
- 🟡 **Super Nova (Timed Diamond):** High-value pickup that instantly refills 100% boost energy and awards +500 points.
- 🟣 **Ghost Phase (G Capsule):** Renders your body intangible, allowing you to pass through your own tail unharmed.
- 🟢 **Magnet Field (M Capsule):** Generates a localized gravitational field pulling nearby orbs directly to you.
- 🔴 **Hyper Drive (H Capsule):** Instantly accelerates your combo multiplier up to **8.0x**.

---

## 🛠️ Architecture & Technical Highlights

- **Single-File Zero Dependency Engine:** Self-contained in one file with no external CSS, fonts, or JS bundles.
- **Real-Time Audio Synthesis:** Complete procedural sound engine using the native Web Audio API (no `.mp3` or `.wav` asset downloads).
- **Input Buffer Queue:** Eliminates input latency and ensures high-speed multi-key turns execute without loss.
- **Sub-Tick Interpolation:** Smooth 60 FPS rendering regardless of the discrete logic tick rate.
- **Persistent Leaderboard:** Saves high scores, multipliers, and run stats locally via `localStorage`.

---

## 📌 Versioning Roadmap

This project follows a stepped versioning system:
- **`1.0`** *(Current Initial Release)*
- **`1.01`** *(Minor adjustments / patches)*
- **`1.1`** *(Major feature release)*
- **`1.11`** *(Follow-up patch / fixes)*

---

## 📜 License

Distributed under the **GNU General Public License v3.0 (GPL-3.0)**. See the `LICENSE` file for more details.
