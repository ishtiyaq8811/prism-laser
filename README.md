# ⚡ Prism Laser: Quantum Optics

An engaging, futuristic optical physics and laser reflection puzzle game built with pure HTML5 Canvas, modern CSS3 Glassmorphism, and Vanilla JavaScript. Features real-time multi-beam ray-tracing, 90° mirror deflection, beam splitters, additive primary color synthesis (RGB → CMY & White), quantum wormholes, 25 progressive handcrafted chambers, an endless procedural laboratory, and pure Web Audio API procedural sound synthesis with **zero external dependencies, libraries, or API keys**!

![Game Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Tech](https://img.shields.io/badge/Tech-HTML5%20Canvas%20%7C%20Vanilla%20JS-orange)
![Genre](https://img.shields.io/badge/Genre-Brain%20%26%20Strategy%20Puzzle-blueviolet)
![Audio](https://img.shields.io/badge/Audio-Web%20Audio%20API-cyan)
![Dependencies](https://img.shields.io/badge/AI%20API%20Key-None%20Required-success)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🌐 Live GitHub Pages Demo
Play the game instantly in your browser:
**https://ishtiyaq8811.github.io/prism-laser/**

---

## ✨ Features & Game Mechanics

### 🔬 Optical Elements & Physics Simulation
- 🔴 **Laser Emitters:** Continuously emit high-energy coherent beams in cardinal directions (Up, Right, Down, Left) across various optical wavelengths.
- 💎 **Resonator Crystals (Targets):** Hexagonal quantum cores that absorb laser energy. When illuminated by light of the exact target frequency/color, they activate, emitting glowing radial shockwaves and harmonic chimes.
- 🪞 **Silver Mirrors:** Diagonal reflective elements that deflect incoming light beams at 90-degree angles. Click or tap to toggle between `/` and `\` orientations.
- 🔺 **Prism Splitters:** Advanced semi-transparent prisms that transmit 50% of the beam straight through while deflecting the remaining 50% orthogonally!
- 🟡 **Color Filters & Additive Mixing:** 
  - Primary colors: Red (1), Green (2), Blue (4).
  - Additive light mixing: 
    - `Red + Green = Yellow`
    - `Green + Blue = Cyan`
    - `Red + Blue = Magenta`
    - `Red + Green + Blue = White`
  - Colored filters isolate specific wavelengths and absorb incompatible frequencies.
- 🌀 **Quantum Portals:** Paired spatial wormholes. Any beam entering Portal A instantaneously exits Portal B traveling in the identical vector trajectory!
- 🧱 **Obstacle Blocks:** Dense cyber-chassis walls that absorb light and require careful perimeter routing.

### 🎮 Game Modes
1. **Chamber Campaign (25 Handcrafted Levels):**
   - **Chambers 1–5:** Photonic Fundamentals & Single-Beam Reflections.
   - **Chambers 6–10:** Prism Splitting & Multi-Core Targeting.
   - **Chambers 11–15:** Additive Color Synthesis & Primary Filters.
   - **Chambers 16–20:** Spatial Redirection via Quantum Portals.
   - **Chambers 21–25:** Grandmaster Quantum Singularity Challenges.
2. **Procedural Quantum Lab (Endless Mode):**
   - Click **🛠️ Quantum Lab** at any time to generate an infinite variety of randomized, procedural optical chambers.
3. **Move Efficiency & 3-Star Rating System:**
   - ⭐⭐⭐ **Gold 3-Star:** Solved within optimal par moves.
   - ⭐⭐ **Silver 2-Star:** Solved within par + 2 moves.
   - ⭐ **Bronze 1-Star:** Chamber solved.
4. **Move History & Undo Support:**
   - Full state snapshotting allows step-by-step undoing of moves.

### 🎵 100% Procedural Web Audio API Sound
- Zero external MP3/WAV assets; all sound effects are generated on-the-fly via mathematical oscillators:
  - **Crystal Singing Bowl Chime:** Resonant harmonic pentatonic scale frequencies triggered when cores power on.
  - **Mechanical Rotation Click:** High-frequency filtered frequency drop.
  - **Placement Thud:** Warm resonant sine pulse.
  - **Victory Arpeggio:** Uplifting multi-oscillator major pentatonic flourish.
  - **Ambient Synth Drone:** Toggleable atmospheric laboratory background hum.

### 📱 100% Responsive & Touch Optimized
- Seamless scaling across smartphones, tablets, and 4K desktop displays.
- Touch-friendly controls: Tap an inventory tool, then tap a grid cell to deploy; tap placed tools to rotate; right-click or drag to return items.

---

## 🕹️ How to Play

1. **Select a Tool:** Click or tap any available optical tool from the **Optical Inventory** dock at the bottom.
2. **Deploy onto the Grid:** Click or tap an empty grid cell to place the selected mirror, splitter, or filter.
3. **Rotate Elements:** Tap an existing player-placed optical element on the grid to cycle its diagonal angle.
4. **Recall Elements:** Right-click (desktop) or tap to remove an element and return it to your inventory.
5. **Power All Cores:** Guide the laser beam(s) so that every Resonator Crystal is energized with its required color.

---

## 🛠️ Local Development & Quick Start

Because **Prism Laser** is a completely self-contained single-file web application, no build steps, bundlers, or package managers are required.

### Run Locally:
```bash
# Clone the repository
git clone https://github.com/ishtiyaq8811/prism-laser.git
cd prism-laser

# Open directly in any modern browser
open index.html   # On macOS
start index.html  # On Windows
xdg-open index.html # On Linux
```

Or serve via any static HTTP server:
```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx serve .
```

---

## 🚀 GitHub Pages Deployment

To enable GitHub Pages for this repository:
1. Navigate to the repository on GitHub: `https://github.com/ishtiyaq8811/prism-laser`.
2. Go to **Settings** > **Pages** (under the "Code and automation" section).
3. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. Your game will be live within seconds at:
   `https://ishtiyaq8811.github.io/prism-laser/`

---

## 📄 License
Released under the [MIT License](LICENSE). Created autonomously by the Autonomous AI Game Factory Agent.
