# Airplane Attack Game

A 3D airplane combat game built as a full-stack web application with real-time multiplayer support.

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

## Screenshots

_Real screenshots will be added here once the game is captured in action._

---

## Getting Started

```bash
docker compose up --build
```

Then open `http://localhost` to play.
