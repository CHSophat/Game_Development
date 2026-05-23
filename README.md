# Airplane Attack Game

![Airplane Attack banner](docs/images/banner.svg)

---

## Introduction

**Airplane Attack** is a browser-based 3D aerial combat game built as a full-stack web application. You strap into one of four real-world inspired fighter jets — **F-16**, **F-22**, **Su-57**, or a custom **Stealth** prototype — and take on waves of enemies, bombers, and end-of-level bosses across five distinct maps.

The game runs entirely in the browser using **Three.js** for real-time 3D rendering, with a **Node.js + Socket.io** backend powering multiplayer matches, persistent player profiles, and a global online leaderboard backed by **PostgreSQL**. Everything is wired up through **Docker Compose** so the full stack — frontend, backend, database, and reverse proxy — boots with a single command.

### What makes it different

- **No installs, no launcher** — point a browser at the URL and you're flying.
- **Cross-input** — keyboard + mouse on desktop, touch joystick + on-screen buttons on mobile, with tilt support.
- **Real audio without external downloads** — the game ships with a synthesized Web Audio music + SFX engine, so background music, key clicks, missile launches, and explosions all work out of the box even if no `.mp3` files are present.
- **Always-on control HUD** — every control key is shown on-screen with a matching symbol while you fly, so first-time players never have to memorise a key list.
- **Dual game modes** — Mission (objectives + boss fight) and Survival (escalating waves), plus PvP and Team multiplayer rooms.

### Who it's for

- Players who want a quick "open-and-play" arcade shooter that runs anywhere a browser does.
- Web developers studying a complete, opinionated full-stack template (auth, sockets, ORM, leaderboard, Docker, Nginx).
- Anyone wanting to fork a 3D web game and bolt on their own jets, weapons, or maps.

---

## Technology Stack

| Layer        | Tech                                                          |
|--------------|---------------------------------------------------------------|
| **Frontend** | React 18, TypeScript, Three.js, Vite, Zustand                 |
| **Backend**  | Node.js 20, Express, Socket.io, TypeORM, JWT                  |
| **Database** | PostgreSQL 16                                                 |
| **Infra**    | Docker Compose, Nginx (reverse proxy)                         |
| **Docs**     | Swagger / OpenAPI (auto-generated from JSDoc)                 |

---

## Core Features

- **Main Menu & Jet Selection** — F-16, F-22, Su-57, and Stealth aircraft
- **Game Modes** — Mission, Survival, Multiplayer (PvP / Team)
- **Weapons System** — Machine gun, missiles, laser, bombs
- **Enemy Variety** — Small, fast, heavy bomber, and boss enemies
- **Maps** — Ocean, Desert, Snow, City, Night Sky
- **Dynamic Weather** — Rain, clouds, thunder effects
- **Upgrade System** — Engine, armor, missile, fuel, radar improvements
- **Reward System** — Coins, XP, and daily rewards
- **Mobile Controls** — Virtual joystick, fire button, and tilt support
- **Online Leaderboard** — Real-time global rankings
- **In-Game HUD** — Always-visible control symbols, audible key feedback, synthesized background music

---

## Screenshots

> All images below are real renderings of the game's own UI components and HUD, drawn directly from this repository — no stock or placeholder photography.

### Main Menu

![Main menu](docs/images/main-menu.svg)

### Jet Selection

![Jet selection](docs/images/jet-selection.svg)

### Gameplay HUD

![Gameplay HUD](docs/images/gameplay.svg)

---

## Controls

| Key       | Symbol | Action              |
|-----------|--------|---------------------|
| `W` / `S` | ↑ / ↓  | Pitch up / down     |
| `A` / `D` | ← / →  | Yaw left / right    |
| `Q` / `E` | ↺ / ↻  | Roll left / right   |
| `Shift`   | »      | Boost               |
| `Space`   | ✦      | Fire gun            |
| `R`       | ➤      | Lock & fire missile |
| `B`       | ◉      | Drop bomb           |
| `L`       | ≣      | Fire laser          |
| `Esc`     | ✕      | Pause / menu        |

The control panel is displayed on the right side of the screen during gameplay. A short audible click confirms every key press.

---

## Future Plans

- [ ] **VR / AR Support** — Immersive cockpit experience with VR headsets
- [ ] **Clan & Squadron System** — Create teams, clan wars, and squadron rankings
- [ ] **Voice Chat** — In-game voice communication for team modes
- [ ] **AI-Powered Enemies** — Smarter enemy behavior using machine learning
- [ ] **Custom Jet Skins & Workshop** — Player-created liveries and skins marketplace
- [ ] **Seasonal Events & Battle Pass** — Limited-time missions and rewards
- [ ] **Cross-Platform Play** — Native iOS and Android clients
- [ ] **Replay & Spectator Mode** — Record matches and watch live games
- [ ] **Tournament System** — Scheduled competitive events with prizes
- [ ] **Advanced Physics Engine** — Realistic flight dynamics and damage modeling

---

## Getting Started

```bash
docker compose up --build
```

Then open `http://localhost` to play.
