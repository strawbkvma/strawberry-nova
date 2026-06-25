# 🍓 Strawberry Nova

A cozy, pastel-colored arcade space shooter. Pilot a strawberry-shaped ship, auto-blast through a galaxy of cute "crumb" enemies, dodge their sparks, and chase a high score — all in a single self-contained HTML file.

<!-- Add a screenshot or short GIF of gameplay here, e.g. -->
<!-- ![Strawberry Nova gameplay](docs/screenshot.png) -->

## ✨ Features

- 🚀 Auto-firing ship — just focus on dodging, the blasting takes care of itself
- 🖱️ Drag-to-move controls that work with mouse, touch, or keyboard
- 👾 Two enemy types with distinct speed, movement, and attack patterns
- 🥛 A milk-drop power-up for temporary double-fire
- ✨ Particle effects, a twinkling starfield, and drifting nebula background
- 🏆 High score that's automatically saved between sessions
- 📱 Fully responsive — playable on desktop and mobile
- 🧩 No build tools or libraries — just one HTML file (plus a Google Fonts import)

## 🎮 How to Play

| Action | Desktop | Mobile |
|---|---|---|
| Move | `←` `→` or `A` `D` | Drag your finger |
| Fire | Automatic | Automatic |
| Start / Restart | `Space` or `Enter` | Tap the button |

Dodge the crumb enemies and their projectiles, grab the milk-drop power-up when it floats by, and survive as long as you can with your 3 lives.

## 🛠️ Tech Stack

- HTML5 Canvas (2D rendering)
- Vanilla JavaScript — no frameworks, no build step
- CSS for UI overlays and responsive scaling
- [Google Fonts](https://fonts.google.com/) — Press Start 2P & Nunito

## 🚀 Getting Started

### Play locally

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

Then just open `strawberry_nova.html` in any modern browser. No server or build step needed.

### Play online with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and the `/ (root)` folder.
4. Your game will be live at:

   ```
   https://<your-username>.github.io/<your-repo>/strawberry_nova.html
   ```

## 📁 Project Structure

```
.
├── strawberry_nova.html   # entire game: markup, styles, and game logic
├── README.md
└── LICENSE
```

## 🎨 Customization

Most of the tunable bits live near the top of the `<script>` block in `strawberry_nova.html`:

| What | Where |
|---|---|
| Color palette | `COL` object |
| Internal canvas resolution | `W`, `H` constants |
| Player move speed | `SPEED` inside `update()` |
| Difficulty / spawn rate over time | `spawnInterval()` |
| Power-up frequency | `powerupTimer` reset value |

## 📄 License

Released under the [MIT License](LICENSE) — free to use, modify, and share.

## 🙏 Credits

Built by **[your name / Strawbkvma]** 🍓
