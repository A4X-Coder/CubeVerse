<div align="center">

# 🧊 CUBEVERSE

### Endless Dimensional Drift — a 3D endless cube runner

Dodge neon obstacles, chase near-misses, and beat your personal best.
Runs instantly in your browser — **no install, no sign-up**.

### [▶️ Play Now → a4x-coder.github.io/CubeVerse](https://a4x-coder.github.io/CubeVerse/)

![Three.js](https://img.shields.io/badge/Three.js-r128-black?logo=three.js&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Desktop-00f0ff)
![Single File](https://img.shields.io/badge/Build-Single%20HTML%20file-8a2be2)
![Dependencies](https://img.shields.io/badge/Dependencies-0%20to%20install-ff2a85)

</div>

---

## ✨ About

**CUBEVERSE** is a relaxing yet addictive 3D endless runner. You control a glossy cyan cube rolling down a glowing neon track toward a rotating portal on the horizon. Switch lanes, slip through gaps, and survive as the world speeds up.

The whole game is a single `index.html` file — graphics are rendered with [Three.js](https://threejs.org/) and all music and sound effects are synthesized live with the Web Audio API, so there are no images or audio files to download.

## 🎮 How to Play

You have **three lanes**. Obstacles come at you in patterns — always leaving at least one reachable gap. Change lanes to dodge. Hit an obstacle and it's game over.

### Controls

| Platform | Action | Input |
|---|---|---|
| 🖥️ Desktop | Move left / right | `←` `→` or `A` `D` |
| 🖥️ Desktop | Pause / resume | `P` or `Esc` |
| 🖥️ Desktop | Start / restart | `Enter` or `Space` |
| 📱 Android / Mobile | Move left / right | Swipe left or right |
| 📱 Android / Mobile | Move left / right | Tap the left or right half of the screen |
| 📱 Android / Mobile | Pause | Pause button (top-right) |

### Scoring

- **Distance** — your score grows the farther you travel.
- **Near Miss +50** — scrape past an obstacle group in the adjacent lane for a bonus.
- **Speed** — the game gradually speeds up, from **1.0×** up to about **2.2×**.
- **Personal Best** — saved automatically in your browser (`localStorage`).

## 🚀 Features

- 🧊 Glossy 3D cube with rolling motion and banking tilt on lane changes
- 🌌 Neon grid track, horizon portal, floating cyber-dust particles and crash shards
- 🎵 Procedural ambient soundtrack and sound effects — zero audio files
- ⚖️ Fair obstacle generation — every pattern keeps a reachable safe lane
- 🎯 Swept collision detection — no tunnelling through obstacles at high speed
- 📱 Mobile-first controls: instant swipe, tap-sides, safe-area (notch) support, portrait camera
- ⚡ Adaptive resolution — automatically lowers render scale if frame rate drops
- ⏸️ Auto-pause when you switch tabs or apps
- 🔇 One-tap mute
- 🏆 Persistent high score

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Rendering | [Three.js r128](https://threejs.org/) (WebGL) |
| Audio | Web Audio API (synthesized, look-ahead scheduled) |
| UI | Vanilla HTML + CSS (glassmorphism) |
| Logic | Vanilla JavaScript — no frameworks, no build step |
| Storage | `localStorage` |

## 💻 Run Locally

No build tools needed.

```bash
# 1. Clone the repo
git clone https://github.com/a4x-coder/CubeVerse.git
cd CubeVerse

# 2. Open the game
# Option A: just double-click index.html
# Option B: serve it locally
python -m http.server 8000
# then open http://localhost:8000
```

> **Note:** Three.js is loaded from the cdnjs CDN, so an internet connection is required the first time you load the game.

## 🌐 Deploy on GitHub Pages

1. Push `index.html` to the root of your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then click **Save**.
5. After a minute, your game will be live at `https://<your-username>.github.io/<repo-name>/`.

## 📁 Project Structure

```
CubeVerse/
├── index.html   # The entire game (HTML + CSS + JS)
└── README.md    # You are here
```

## 🧩 Browser Support

Works on any modern browser with **WebGL** enabled:

- Chrome / Edge (Android & Desktop)
- Firefox
- Safari

If WebGL can't start, the game shows an error message instead of a blank screen.

## 🔧 Tuning the Game

Want to tweak the feel? These constants are near the top of the script in `index.html`:

| Constant | What it does | Default |
|---|---|---|
| `BASE_SPEED` | Starting speed | `24` |
| `MAX_SPEED` | Top speed cap | `54` |
| `LANE_WIDTH` | Distance between lanes | `2.4` |
| `CUBE_SIZE` | Size of the player cube | `1.2` |

## 🗺️ Ideas for the Future

- [ ] Power-ups (shield, slow-motion, score multiplier)
- [ ] Multiple cube skins and track themes
- [ ] Jump / duck obstacles
- [ ] Online leaderboard
- [ ] Installable PWA with offline support

## 🤝 Contributing

Issues and pull requests are welcome. If you spot a bug or have an idea, open an issue and describe what happened and which device and browser you used.

## 📄 License

Released under the [MIT License](LICENSE). Add a `LICENSE` file to the repo to make this official, or swap in the license you prefer.

---

<div align="center">

Made with ❤️ by **a4x-coder**

⭐ If you enjoyed CUBEVERSE, star the repo!

**[▶️ Play Now](https://a4x-coder.github.io/CubeVerse/)**

</div>
