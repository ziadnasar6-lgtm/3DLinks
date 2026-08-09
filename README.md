# 🌌 Nassar Gate | 3D Cyber Personal Hub & Link Tree

![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js)
![WebGL](https://img.shields.io/badge/WebGL-3D%20Graphics-990000?style=for-the-badge&logo=webgl)
![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-Procedural%20Sound-00f2fe?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Welcome to **Nassar Gate**! I designed and developed this lightweight, ultra-modern 3D Personal Hub and Link Tree from scratch using pure **HTML**, **CSS**, **JavaScript**, **Three.js**, and the **Web Audio API**. 

Unlike standard static 2D link trees, **Nassar Gate** suspends bold 3D extruded brand emblems and 3D typography floating in a dark cosmic starfield. It features real-time 360° self-spin interaction, native page scroll synchronization, dynamic glowing arrow controls, and zero external audio dependencies.

---

## ✨ Key Features

- **🌐 Pure 3D Sculptural Text & Icons**: Heavy 3D extruded brand emblems (Facebook, WhatsApp, YouTube, GitHub, Nassar 3D Gate, Nassar Gate) and bold 3D text rendered directly in WebGL space.
- **🎯 Perfect Horizontal Alignment**: All 3D items are strictly locked to the center (`X = 0`) across all device screen sizes.
- **🔄 360° Self-Spin Physics**: Dragging or swiping horizontally over any 3D item spins it gracefully around its own vertical Y-axis in place.
- **🔊 Procedural Web Audio Synthesis**: High-frequency crystal glass chime sound FX synthesized programmatically with Web Audio API oscillators (`Sine`/`Triangle`) with zero external `.mp3` or `.wav` files.
- **📜 Smooth Native Window Scroll Sync**: Seamless camera Y-tracking mapped directly to browser window scrolling.
- **✨ Glowing Arrow Navigation**: Neon glowing arrow buttons (`↑` / `↓`) and quick-jump dot indicators for fast item progression.
- **📱 Mobile-First Responsive Design**: Optimized FOV, camera distance, and touch event handling tailored specifically for mobile phone screens.

---

## 🛠️ Tech Stack

- **Core**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: Modern CSS3 (Glassmorphism, Backdrop Filters, Neon Glows, CSS Grid & Flexbox)
- **3D Graphics Engine**: [Three.js r128](https://threejs.org/) (WebGL Renderer, ExtrudeGeometry, TextGeometry, PointLights, Particles)
- **Animations**: [GSAP 3.12](https://greensock.com/gsap/) (Spring physics & camera/window scroll interpolation)
- **Audio Engine**: Native Web Audio API (AudioContext & Oscillators)

---

## 🚀 Quick Start (Local Setup)

Because **Nassar Gate** is built as a single clean production HTML file (`index.html`), no build steps or `npm install` commands are required!

### Option 1: Direct File Launch
Simply double-click `index.html` in your file explorer to open it in your default web browser.

### Option 2: Run via Local Development Server
Using Node.js or Python:

```bash
# Using Python
python -m http.server 8080

# Or using Node npx
npx serve . -p 8080
```

Then open `http://localhost:8080` in your web browser.

---

## ⚙️ How to Customize Your Links

At the top of the `<script>` tag in [`index.html`](index.html), locate the `LINKS` object and replace the placeholder URLs with your personal social links:

```javascript
/* ========================================================================
   1. SOCIAL & PORTFOLIO LINKS CONFIGURATION (CUSTOMIZE HERE)
   ======================================================================== */
const LINKS = {
  facebook: "https://facebook.com/YOUR_PROFILE",
  whatsapp: "https://wa.me/YOUR_PHONE_NUMBER",
  youtube: "https://youtube.com/@YOUR_CHANNEL",
  github: "https://github.com/YOUR_USERNAME",
  portfolio3D: "https://YOUR_3D_PORTFOLIO_URL", // Nassar 3D Gate
  portfolio2D: "https://YOUR_2D_PORTFOLIO_URL"  // Nassar Gate
};
```

---

## 📂 Project Structure

```text
LinksCard/
├── index.html     # Single-file complete production WebGL hub (HTML, CSS, JS)
└── README.md      # Project documentation & setup guide
```

---

## 👤 Author

Developed with passion by **Nassar**  
*Creator of Nassar Gate & Nassar 3D Gate*

- **GitHub**: [github.com](https://github.com)
- **3D Hub**: [Nassar 3D Gate](https://threejs.org)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
