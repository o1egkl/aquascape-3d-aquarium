# 🐠 AquaScape 3D — Photorealistic Living Aquarium (6 Species Edition)

[![Live Demo on GitHub Pages](https://img.shields.io/badge/Live_Demo-GitHub_Pages-06b6d4?style=for-the-badge&logo=github)](https://o1egkl.github.io/aquascape-3d-aquarium/)
[![Three.js WebGL](https://img.shields.io/badge/Three.js-r128_WebGL-4f46e5?style=for-the-badge&logo=threedotjs)](https://threejs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](./LICENSE)

An interactive, single-file **3D Photorealistic WebGL Aquarium** built with **Three.js** and custom GLSL vertex/fragment shaders. All fish geometries, overlapping cycloid scale bump maps, striated translucent veil fins, water caustics, and swaying aquatic flora are **100% procedurally generated in real time** with zero external texture or 3D model dependencies.

---

## ✨ Key Features

### 🐟 6 Anatomically Sculpted Fish Species
1. **Symphysodon Discus (*Royal Turquoise & Cobalt*)**: Laterally compressed circular-disk body with glowing turquoise vermiculated labyrinth stripes, ruby-red iris eyes, and continuous sweeping dorsal/anal fins.
2. **Betta Splendens (*Halfmoon Siamese Fighting Fish*)**: Iridescent metallic dragon-scale body with 180-degree billowing Halfmoon veil caudal, dorsal, and skirt anal fins.
3. **Pterophyllum Scalare (*Altum Angelfish*)**: High-fin diamond-disc silver-pearl body with golden crown, vertical zebra bars, sculpted gill operculum, and long trailing pelvic feelers.
4. **Carassius Auratus (*Fancy Oranda & Kohaku Goldfish*)**: Plump sculpted body with cranial wen, high-gloss cycloid scales, and split double-veil fantails.
5. **Paracheirodon Axelrodi (*Schooling Cardinal Tetras*)**: Tightly schooling Amazonian tetras powered by Boids cohesion, alignment, and separation AI.
6. **Chromobotia Macracanthus (*Bottom-Foraging Clown Loaches*)**: Tiger-striped bottom cruisers with sensory rostral barbels that forage right above the river pebbles and contoured sand.

### 🌊 Custom Underwater GLSL Shaders & Environment
- **Real-Time Water Caustics**: Projected onto the contoured sandy bottom and river boulders.
- **Biomechanical Carangiform Swim Shader**: Smooth S-wave spinal undulation and fin-ripple propagation synchronized with each fish's velocity.
- **Swaying Aquatic Flora**: Instanced *Vallisneria* ribbon grass, *Amazon Sword* rosettes, and *Red Ludwigia* plants swaying organically in the water current.
- **Responsive & Mobile-Optimized**: Automatic portrait/landscape FOV framing, collapsible HUD drawer, touch tap-to-feed, and a 3-tier Performance Mode governor (`Auto`, `High`, `Eco`).

---

## 🎮 Interactive Controls

| Control / Action | Description |
| :--- | :--- |
| **Click / Tap Water** | Scatters sinking food pellets that fish actively swim toward and eat |
| **Species Badges (Bottom Bar)** | Locks the Close-Up Macro Inspector Camera onto any of the 6 fish species |
| **+ Spawn Menu** | Dynamically spawns additional fish of any species into the tank |
| **⚡ Quality Toggle** | Cycles between `Auto`, `High` (2x Retina + soft shadows), and `Eco` (60 FPS mobile saver) |
| **☀️ / 🌙 Lighting Mode** | Switches between Tropical Daylight god-rays and deep bioluminescent Moonlight |

---

## 🚀 Running Locally or Deploying to GitHub Pages

Because the entire application is self-contained inside `index.html`, no build step or bundler is required:

1. Clone this repository:
   ```bash
   git clone https://github.com/o1egkl/aquascape-3d-aquarium.git
   cd aquascape-3d-aquarium
   ```
2. Open `index.html` directly in any modern browser, or serve it locally:
   ```bash
   npx serve .
   ```
3. **GitHub Pages**: Enable GitHub Pages in **Settings → Pages → Deploy from branch (`main` / `root`)**.

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for details.
