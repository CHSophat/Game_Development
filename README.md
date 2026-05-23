# Airplane Attack Game

A 3D airplane combat game built as a full-stack web application with real-time multiplayer support.

---

## Introduction

**Airplane Attack** is a browser-based 3D aerial combat game. Pick one of four fighter jets (F-16, F-22, Su-57, Stealth), fly across five maps, and fight enemies, bombers, and bosses solo or against other players online. The whole stack runs in Docker — `docker compose up --build` and you're flying at `http://localhost`.

---

## Technology Stack

Every badge below is a real, browser-openable image URL served by [shields.io](https://shields.io) — click any image to view it directly in your browser.

### Frontend

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
[![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
[![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=react&logoColor=white)](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=react&logoColor=white)

### Backend

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
[![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
[![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
[![TypeORM](https://img.shields.io/badge/TypeORM-E83524?style=for-the-badge&logo=typeorm&logoColor=white)](https://img.shields.io/badge/TypeORM-E83524?style=for-the-badge&logo=typeorm&logoColor=white)
[![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### Database

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### Infra & Tooling

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
[![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### Summary Table

| Layer        | Tech                                           |
|--------------|------------------------------------------------|
| **Frontend** | React 18, TypeScript, Three.js, Vite, Zustand  |
| **Backend**  | Node.js 20, Express, Socket.io, TypeORM, JWT   |
| **Database** | PostgreSQL 16                                  |
| **Infra**    | Docker Compose, Nginx (reverse proxy)          |
| **Docs**     | Swagger / OpenAPI (auto-generated from JSDoc)  |

---

## Getting Started

```bash
docker compose up --build
```

Then open `http://localhost` to play.
