# ⚡ Sampreeth Mysore Prabhu Shankar — Portfolio

> *"I build things that scale, think, and feel."*

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-sampreeth006.github.io-00BFFF?style=for-the-badge)](https://sampreeth006.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-Sampreeth006-181717?style=for-the-badge&logo=github)](https://github.com/Sampreeth006)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-sampreethmp006-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/sampreethmp006)
[![Email](https://img.shields.io/badge/Email-smysorep@gmu.edu-FF3A6E?style=for-the-badge&logo=gmail)](mailto:smysorep@gmu.edu)

---

## 🎬 About This Portfolio

This isn't your average portfolio — it's a **cinematic spy-movie-style experience** inspired by the Saaho film intro sequence. Built entirely in vanilla HTML, CSS, and JavaScript with zero frameworks.

### The Experience
```
🔐 UNAUTHORIZED ACCESS screen
    ↓
💻 Matrix hacking sequence (2.7s)
    ↓
🎵 Saaho theme music kicks in
    ↓
📡 7 cinematic scenes with full-bleed photos + HUD overlays
    ↓
📊 Classified DOSSIER reveal with your profile
    ↓
🚀 ACCESS PROFILE → full portfolio
```

---

## ✨ Features

### 🎭 Cinematic Intro
- **Matrix code rain** (Japanese katakana + binary) with RGB chromatic aberration
- **7 full-screen spy-briefing scenes** — each photo treated as intel evidence with:
  - Ken Burns zoom/pan animations (4 directions)
  - HUD overlays: coordinates, signal bars, live UTC clock, decryption counter
  - Classified data panels, code terminals, target locators
- **Project evidence pop-ups** during the Weapons Expertise scene — 3 project screenshots flash as translucent holographic intel (screen blend mode)
- **Saaho theme audio** (25–35s clip, embedded as base64)
- **Synthesized sound effects** — riser tones, glitch noise, impact beeps via Web Audio API
- **Identity Tracking Document** dossier reveal with profile photo + full info grid

### 🌐 Portfolio Body
- **Three.js wireframe globe** in the hero — mouse-reactive, auto-rotates
- **Liquid ink pipe skills** — animated fill with bubble shimmer and wave pulse (no numeric percentages)
- **Drag-scroll project rail** — horizontal cards with image carousel support (multi-image per project)
- **Dual-column experience timeline**
- **Scroll-reveal animations** on all sections

### 📸 Smart Image Loading
Projects support multi-image carousels with zero configuration:
```
project01.jpg     ← main image
project01a.jpg    ← slide 2 (auto-detected)
project01b.jpg    ← slide 3 (auto-detected)
project01c.jpg    ← slide 4 (auto-detected)
```
Upload named images to the repo — the carousel builds itself automatically.

---

## 🛠️ Tech Stack

```
HTML5 · CSS3 · Vanilla JavaScript · Three.js (r128)
Web Audio API · CSS Custom Properties · Intersection Observer API
```

**No frameworks. No build tools. No dependencies beyond Three.js.**

---

## 🚀 Projects Featured

| # | Project | Tech |
|---|---|---|
| 01 | **Laakksh — Outreach Hub** | React.js, Node.js, Tailwind, Supabase |
| 02 | **Stable Diffusion + DiT Image Generation** | Python, PyTorch, HuggingFace, Docker, AWS ECS |
| 03 | **AI-Inspired Homework Grader** | React.js, Tailwind, Jest, Selenium |
| 04 | **Modern Resume Builder** | HTML/CSS/JS, Flask, Docker, jsPDF |
| 05 | **SwiftMarket — Instant Market Online Store** | HTML5, Bootstrap 5, JavaScript, localStorage |
| 06 | **UI Code Assistant** | HTML5, Bootstrap 5, jQuery, localStorage |
| 07 | **K.LA.S.H Bot — IoT Military Intelligence** | IoT, Python, Random Forest, Linear Regression |
| 08 | **Inventory Management (Android)** | Java, Android Studio, SQLite |
| 09 | **Online Railway Reservation System** | PHP, MySQL, HTML/CSS |

---

## 👤 About Me

**Sampreeth Mysore Prabhu Shankar**
📍 Fairfax, Virginia, USA

MS in Computer Science @ **George Mason University** (Jan 2025 – Dec 2026)
BE in Computer Science @ **ATME College of Engineering**, Mysuru (2019 – 2023)

**Experience:**
- 💼 Software Engineer — *RideNext Software Solutions Pvt. Ltd.*, Bangalore (Oct 2023 – May 2024)
- 💼 Software Engineering Intern — *Compsoft Technologies*, Mysuru (Aug 2021 – Oct 2021)

**Specializations:** AI/ML · Full Stack Engineering · UI/UX Design · IoT Systems

---

## 📂 Project Structure

```
sampreeth006.github.io/
│
├── index.html          ← The entire portfolio (self-contained)
│
├── project01.jpg       ← Laakksh screenshot
├── project01a.jpg      ← Laakksh screenshot 2 (carousel)
├── project02.jpg       ← Stable Diffusion output
├── project03.jpg       ← AI Grader screenshot
├── project04.jpg       ← Resume Builder screenshot
├── project05.jpg       ← SwiftMarket screenshot
├── project06.jpg       ← UI Code Assistant screenshot
├── project07.jpg       ← K.LA.S.H Bot photo
├── project08.jpg       ← Inventory App screenshot
└── project09.jpg       ← Railway Reservation screenshot
```

> **Note:** `index.html` is fully self-contained — all fonts, photos, audio, and the profile image are embedded as base64. No CDN dependencies except Three.js and Google Fonts.

---

## 🖥️ Running Locally

No build step needed. Just open:

```bash
git clone https://github.com/Sampreeth006/sampreeth006.github.io
cd sampreeth006.github.io
open index.html   # macOS
# or
start index.html  # Windows
# or just drag index.html into your browser
```

> ⚠️ **Audio note:** The Saaho theme audio plays after clicking **INITIATE**. If it doesn't play in a local file:// context, deploy to GitHub Pages or serve locally with:
> ```bash
> python3 -m http.server 8080
> # then visit http://localhost:8080
> ```

---

## 📌 Keyboard Shortcut

Press **`ESC`** at any time during the intro to skip directly to the portfolio.

---

## 🎨 Design System

| Token | Value | Usage |
|---|---|---|
| `--acc` | `#00BFFF` | Primary accent (cyan) |
| `--acc2` | `#FF3A6E` | Alert / evidence (red) |
| `--acc3` | `#7B61FF` | Education / purple |
| `--acc4` | `#FFB800` | DevOps / yellow |
| `--bg` | `#02060c` | Background |
| Font 1 | Bebas Neue | Headings, counters |
| Font 2 | Space Grotesk | Body, UI |
| Font 3 | JetBrains Mono | Code terminals, HUD |

---

## 📄 License

This portfolio is personal work. Feel free to draw inspiration, but please don't copy it wholesale and present it as your own.

---

<div align="center">
  <strong>Built with 🎬 cinematic ambition and ☕ too much coffee</strong><br>
  <em>Sampreeth Mysore Prabhu Shankar · 2025</em>
</div>
