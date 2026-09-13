# [Strawberry Nova](https://strawbkvma.github.io/strawberry-nova/strawberry-nova.html) 🍓🚀

> A cute pastel arcade space shooter built as a single self-contained HTML game.

**Strawberry Nova** is a small and intentionally RANDOM browser game where you pilot a strawberry-shaped ship through a galaxy of cute "crumb" enemies. Dodge incoming sparks, collect milk-drop power-ups, survive with your 3 lives, and chase a high score.

Everything runs directly in the browser. No framework. No build tools. No complicated setup.

<img width="679" height="774" alt="Strawberry Nova gameplay" src="https://github.com/user-attachments/assets/fe1fdcff-1dd8-452b-9189-b8cd714e34c1" />

---

## ✨ Features

* 🚀 Auto-firing strawberry-shaped player ship
* 🖱️ Drag-to-move controls for mouse and touch
* ⌨️ Keyboard controls with `←` `→` or `A` `D`
* 👾 Two enemy types with different movement and attack patterns
* 🥛 Milk-drop power-up with temporary double-fire
* ✨ Particle effects, twinkling stars, and drifting nebula background
* 🏆 High score saved automatically between sessions
* ❤️ 3 lives per run
* 📱 Responsive layout for desktop and mobile
* 🧩 No frameworks or build tools
* 📄 Entire game contained in a single HTML file

---

## 🎮 How to Play

| Action | Desktop | Mobile |
|---|---|---|
| Move | `←` `→` or `A` `D` | Drag your finger |
| Fire | Automatic | Automatic |
| Start / Restart | `Space` or `Enter` | Tap the button |

Dodge the crumb enemies and their projectiles, grab the milk-drop power-up when it appears, and survive as long as you can.

The longer you survive, the higher your score.

---

## 🛠️ Tech Stack

* **HTML5 Canvas** — 2D game rendering
* **Vanilla JavaScript** — game logic and interactions
* **CSS** — UI overlays and responsive scaling
* **Google Fonts** — Press Start 2P & Nunito

Strawberry Nova intentionally keeps the stack simple so the entire game can run from a single HTML file.

---

## 🍓 Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/strawbkvma/strawberry-nova.git
cd strawberry-nova
```

### 2. Play locally

Open `strawberry-nova.html` in any modern browser.

No server, package manager, or build step is required.

### 3. Play online

You can also play Strawberry Nova through GitHub Pages:

[Play Strawberry Nova 🍓](https://strawbkvma.github.io/strawberry-nova/strawberry-nova.html)

That's it. 🍓🚀✨

---

## 📁 Project Structure

```text
strawberry-nova/
│
├── strawberry-nova.html   # entire game: markup, styles, and game logic
├── README.md
└── LICENSE
```

There are no dependency directories or build artifacts required to run the game.

---

## 🎨 Customization

Most gameplay and visual values can be adjusted directly inside `strawberry-nova.html`.

| What | Where |
|---|---|
| Color palette | `COL` object |
| Internal canvas resolution | `W`, `H` constants |
| Player movement speed | `SPEED` inside `update()` |
| Difficulty / enemy spawn rate | `spawnInterval()` |
| Power-up frequency | `powerupTimer` reset value |

Because everything is contained in one file, experimenting with the game's visuals and mechanics is straightforward.

---

## 🐛 Troubleshooting

### The game doesn't start

Make sure you are opening `strawberry-nova.html` in a modern browser such as Safari, Chrome, Firefox, or Edge.

No local server should be required.

### Controls aren't working

Try clicking or tapping the game first, then use `←` / `→`, `A` / `D`, mouse dragging, or touch dragging on mobile.

### My high score disappeared

The high score is saved using browser local storage. Clearing browser site data or local storage may remove the saved score.

---

## 🔒 Privacy

Strawberry Nova is designed to run locally in your browser.

It does **not**:

* require an account or login
* use an external backend
* collect gameplay data
* store personal information
* require a database

The game only uses browser functionality needed to run the game and save your high score locally.

The project imports fonts from Google Fonts when an internet connection is available.

---

## 🏗️ Architecture

Strawberry Nova keeps its entire game inside one HTML file:

```text
Browser
   │
   ▼
strawberry-nova.html
   │
   ├── HTML → game UI
   ├── CSS  → styling & responsive layout
   ├── Canvas → rendering
   └── JavaScript → game logic, input, enemies,
                     power-ups, scoring & local storage
```

This keeps the project lightweight and easy to run, inspect, and modify.

---

## 🗺️ Roadmap

### 🎮 Gameplay

* [x] Auto-firing player ship
* [x] Multiple enemy types
* [x] Enemy projectiles
* [x] Milk-drop power-up
* [x] Lives and scoring system
* [x] High score persistence

### 📱 Platform

* [x] Desktop controls
* [x] Touch controls
* [x] Responsive layout
* [x] GitHub Pages deployment

### 🍓 Future Improvements

* [ ] More enemy types
* [ ] Additional power-ups
* [ ] More visual effects
* [ ] Sound effects and music
* [ ] More difficulty progression

---

## 📜 License

Strawberry Nova is open-source software licensed under the **MIT License**.

See [`LICENSE`](LICENSE) for details.

---

## 🍓 About

Strawberry Nova started as a small experiment in making a cute, simple browser game with a pastel aesthetic and almost zero setup.

The idea is simple:

> Make a tiny space shooter, but make the spaceship a strawberry. 🍓🚀

Made with 🍓, ✨, and probably too much randomness.
