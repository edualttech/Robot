# 🤖 AXON-09 — Interactive Robot Explorer

An interactive, real-time **3D robot** built with Three.js. Explore every part of a humanoid robot, watch it walk, peek inside with X-ray vision, and learn what each component does — in terms that are easy for **everyone**, including young students.

> ⚡ Open `index.html` in a browser and it runs instantly. No build step, no install.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🚶 **Motion & Walk** | The robot walks in real time with a smooth, physics-inspired gait. Toggle walk / idle anytime. |
| 🔍 **Inspect Parts** | Click or hover any component to see what it is. |
| 👶 **Easy Mode** | One click switches to child-friendly explanations — "THE MUSCLE", "THE BRAIN" — perfect for a 3rd-grade classroom. |
| 🩻 **X-Ray Mode** | Fade the polymer shell to reveal the internals: AI chips, battery, cooling fans & cables. |
| 🏷️ **Callout Labels** | Auto-positioned labels connect every part to its technical name. |
| 🔄 **Auto-Orbit** | Sit back and let the robot spin for a full tour. |
| 🧠 **Neural Core** | A live holographic "brain" with pulsing synaptic signals. |
| 📊 **Control Pipeline** | Animated signal-chain panel (Sense → Think → Decide → Act). |

---

## 🎮 Controls

| Action | How |
|--------|-----|
| **Rotate camera** | Drag with the mouse |
| **Zoom** | Scroll wheel |
| **Inspect a part** | Click it (also shows a tooltip on hover) |
| **Toggle Easy Mode** | Press `E` or click **EASY MODE** |
| **Walk / Idle** | Press `Space` or click **MOTION** |
| **X-Ray** | Press `X` or click the button |
| **Callout labels** | Press `L` or click **CALLOUTS** |
| **Auto-orbit** | Click **AUTO-ORBIT** |
| **Reset view** | Press `Esc` or click **RESET VIEW** |

---

## 🚀 Getting Started

Because the project is a **single self-contained HTML file**, there's nothing to install:

1. **Clone** the repo:
   ```bash
   git clone https://github.com/edualttech/Robot.git
   cd Robot
   ```
2. **Open** `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Explore! 🎉

> The project loads the Three.js library from a CDN, so an internet connection is needed on first load.

---

## 🌐 Deploying to Vercel

You can deploy this in seconds:

**Option A — Vercel Dashboard**
1. Push this repo to GitHub (already done).
2. Go to [vercel.com/new](https://vercel.com/new) and **Import** the `Robot` repository.
3. Leave the defaults (framework: **Other**), and click **Deploy**. Done! 🎉

**Option B — Vercel CLI**
```bash
npm i -g vercel
vercel          # first time: sign in, then deploy preview
vercel --prod   # deploy to production
```

---

## 🧰 Tech Stack

- **[Three.js](https://threejs.org/)** — 3D rendering, orbit controls, rounded geometry.
- **HTML5 Canvas** — procedural textures, holographic interface, PCB/battery art.
- **CSS3** — futuristic HUD, callout system, and animations.
- Kudos to the [Room Environment](https://threejs.org/examples/#webgl_materials_room_environment) for studio lighting.

---

## 🏗️ Project Structure

```
Robot/
└── index.html     # The entire app — 3D scene, UI, and logic in one file
```

---

## 👨‍👩‍👧 For Teachers & Parents

This explorer is designed to be **educational and friendly** for children around 3rd grade:

- **Easy Mode** translates technical jargon into simple, relatable ideas (e.g. the battery is *"the power pack that gives the robot energy, just like your snacks give you energy"*).
- Hovering any part reveals a short, plain-language explanation in the top banner.
- It can spark conversations about **engineering, sensors, and how machines think**.

Try asking a child: *"What helps the robot stand up straight?"* → hover **BALANCE SENSOR**. 🎓

---

## 📄 License

This project is for educational and demonstration purposes. Feel free to use, modify, and share it for learning.
