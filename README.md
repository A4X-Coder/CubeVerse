<div align="center">

# 🧊 CUBEVERSE

**Endless Dimensional Drift**

A 3D Endless Cube Runner

*Dodge the obstacles. Chase the near-misses. Survive the drift.*

### [▶ PLAY CUBEVERSE NOW](https://a4x-coder.github.io/CubeVerse/)

![Three.js](https://img.shields.io/badge/3D-Three.js-black?logo=three.js&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Desktop-00d9ff)
![Architecture](https://img.shields.io/badge/Architecture-Single--File-8a2be2)
![Hosting](https://img.shields.io/badge/Hosting-GitHub%20Pages-181717?logo=github)

</div>

<!-- Add a gameplay screenshot or GIF: save it as screenshot.png in the repo, then remove this comment markup.
<div align="center">

![CUBEVERSE gameplay](screenshot.png)

</div>
-->

---

## 🌌 About CUBEVERSE

CUBEVERSE is a browser-based 3D endless runner set in a futuristic neon dimension.

Take control of a glossy cyan cube rolling across a glowing track toward a mysterious portal on the horizon. Switch lanes, dodge incoming obstacles, narrowly escape collisions, and push your survival skills to the limit as the world accelerates around you.

Every run is a new challenge. Every near-miss counts. How far can you drift?

## ✨ Features

- 🧊 **Dynamic 3D Gameplay** — A rolling cube with responsive movement and lane transitions.
- 🌌 **Neon Atmosphere** — Glowing tracks, a futuristic horizon portal, and floating particles.
- 🚧 **Endless Obstacles** — Navigate changing obstacle patterns and search for a safe path.
- ⚡ **Increasing Difficulty** — Survive as the game gradually becomes faster.
- 🎯 **Near-Miss Bonuses** — Get rewarded for narrowly avoiding danger.
- 💥 **Crash Effects** — Experience visual effects when a run ends.
- 🎵 **Procedural Audio** — Browser-generated music and sound effects using the Web Audio API.
- 📱 **Mobile-Friendly Controls** — Swipe or tap to play on mobile browsers.
- 🖥️ **Desktop Support** — Keyboard controls for desktop gameplay.
- 🏆 **Personal Best** — Save your high score locally in your browser.

## 🎮 How to Play

Your goal is simple: survive for as long as possible without hitting an obstacle.

1. Start a run and prepare for incoming obstacles.
2. Switch between lanes to avoid collisions.
3. Look for safe gaps and react quickly.
4. Take advantage of near-miss bonuses.
5. Beat your previous high score and challenge yourself to go further.

## 🕹️ Controls

| Action | Desktop | Android / Mobile |
|---|---|---|
| Move left | `←` or `A` | Swipe left or tap the left side |
| Move right | `→` or `D` | Swipe right or tap the right side |
| Pause / Resume | `P` or `Esc` | On-screen pause button |
| Start / Restart | `Enter` or `Space` | On-screen buttons |

## 🏆 Scoring System

- **Distance Score:** Travel farther to increase your score.
- **Near-Miss Bonus:** Earn **+50** bonus points for narrowly avoiding obstacles.
- **Increasing Speed:** The challenge intensifies as your run progresses.
- **Personal Best:** Your best result is saved in browser storage.

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Structure and single-file packaging |
| CSS3 | Styling, layout, and visual effects |
| JavaScript | Gameplay, movement, and interactions |
| Three.js | 3D rendering using WebGL |
| Web Audio API | Procedural music and sound effects |
| localStorage | Local high-score persistence |

## 📦 Single-File Architecture

CUBEVERSE is packaged in a single `index.html` file containing the HTML, embedded CSS, and embedded JavaScript.

There is no separate CSS file, JavaScript file, or build process required. Three.js is loaded externally from a CDN.

## 🚀 Play Online

Play directly in your browser without installing a separate game application.

### [🧊 Launch CUBEVERSE](https://a4x-coder.github.io/CubeVerse/)

> **Recommended:** Use an up-to-date browser with WebGL support. An internet connection is needed to load the externally hosted Three.js library.

## 💻 Run Locally

You can run the game from a local copy of the repository.

```bash
git clone https://github.com/A4X-Coder/CubeVerse.git
cd CubeVerse
```

Open `index.html` in a modern browser.

Alternatively, if Python is installed, you can serve the folder locally:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

> **Note:** Three.js is loaded from an external CDN, so internet access is required for that dependency.

## 📁 Project Structure

```text
CubeVerse/
├── index.html   # Complete game: HTML, CSS, and JavaScript
└── README.md    # Project documentation
```

## 🌐 Deployment

CUBEVERSE is hosted using GitHub Pages.

To publish your own copy:

1. Upload `index.html` to the root of your repository.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder.
5. Save your settings and wait for deployment to finish.

Your game will then be available through your GitHub Pages URL.

## 🗺️ Future Roadmap

Ideas for future updates:

- [ ] More cube skins and visual customization
- [ ] Additional track themes and environments
- [ ] Power-ups and special abilities
- [ ] New obstacle patterns and gameplay mechanics
- [ ] Online leaderboard and competitive scoring
- [ ] Installable Progressive Web App (PWA)
- [ ] More visual effects and audio options

## 🤝 Feedback & Contributions

Have an idea, found a bug, or want to suggest an improvement?

Visit the [CUBEVERSE repository](https://github.com/A4X-Coder/CubeVerse) to share feedback or open an issue.

## 📄 License

No license is specified in this repository unless a `LICENSE` file is added. Until then, reuse and redistribution permissions should not be assumed.
