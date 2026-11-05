# 🌷 Lily, Compiled

**Something beautiful gets compiled.**

A cinematic 3D flower animation built with **Three.js and Vanilla JavaScript**. The project transforms individual particles into a blooming floral arrangement, featuring realistic-looking petals, soft lighting, glowing particles, and an immersive dark atmosphere.

## ✨ Features

- **3D Flower Animation** – Multiple flowers with procedurally generated petals.
- **Particle-to-Flower Transformation** – Hundreds of glowing particles assemble into a floral structure.
- **Blooming Animation** – Flowers gradually open their petals through custom parametric geometry.
- **Dynamic Lighting** – Ambient, directional, and colored point lights create depth.
- **Wireframe Effects** – Flowers transition between wireframe and solid material appearances.
- **Interactive Rotation** – Drag to rotate the 3D scene.
- **Tap to Replay** – Tap the scene to restart the animation sequence.
- **Ambient Effects** – Floating dust particles, pink glow, and a subtle ground ring.
- **Responsive Rendering** – Automatically adjusts to different screen sizes.
- **Automatic Animation Loop** – The complete visual sequence repeats every 22 seconds.

## 🛠️ Technologies Used

- **HTML5** – Project structure.
- **CSS3** – Dark cinematic background and responsive layout.
- **JavaScript (ES6+)** – Animation logic and interactions.
- **Three.js (r128)** – 3D rendering, geometry, materials, lighting, and particles.
- **WebGL** – Hardware-accelerated 3D graphics.
- **Canvas API** – Procedural petal and leaf textures.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/lily-compiled.git
cd lily-compiled
```

### 2. Run the Project

This is a browser-based project and does not require a build system.

You can open `index.html` directly in a modern browser or use VS Code Live Server.

### 3. Open in Browser

Visit the local URL provided by Live Server.

## 🎮 Controls

| Action | Function |
|---|---|
| Drag horizontally | Rotate the 3D flower arrangement |
| Tap / Click | Replay the animation |
| Wait | Watch the automatic 22-second animation loop |

## 🎨 Animation Sequence

The animation follows a carefully timed visual sequence:

1. **Initialization** – Particles begin appearing in the scene.
2. **Compilation** – Particles move towards their target positions.
3. **Wireframe Formation** – The floral structure takes shape through glowing wireframe geometry.
4. **Blooming** – Petals gradually unfold and reveal the flowers.
5. **Final Transformation** – The particle system and flower geometry transition into the final visual state.
6. **Reset** – The scene fades and prepares for the next animation cycle.

## 📂 Project Structure

```text
lily-compiled/
│
├── index.html
└── README.md
```

## ⚙️ Customization

The animation can be customized directly in the JavaScript source.

| Variable | Purpose |
|---|---|
| `LOOP` | Total animation cycle duration |
| `FD` | Flower positions, rotations, sizes, and textures |
| `NU`, `NV` | Petal geometry resolution |
| `FPS` | Not explicitly configured; animation uses requestAnimationFrame |
| `CAP` | Animated text displayed at the top |
| `M` | Flower and leaf materials |
| `LOOP` | Controls the 22-second animation cycle |

## 🌐 Requirements

- A modern browser with WebGL support.
- Internet connection to load the Three.js CDN dependency.
- Hardware acceleration recommended for smoother rendering.

## 💡 Concept

The idea behind *Lily, Compiled* is to represent something beautiful emerging from seemingly scattered pieces.

Particles assemble, structures form, and flowers bloom — turning a technical process into a visual metaphor.

**Not everything beautiful is created instantly. Sometimes, it has to be compiled.** 🌷

## 📜 License

This project is available for personal learning and experimentation. Add an appropriate license file before distributing it under specific reuse terms.
