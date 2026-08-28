# Multiplayer Game — Codaisseur Capstone (2019)

Final capstone project for the Codaisseur Full Stack Developer program, co-developed with Matias Mateu.

## Overview

[SUBSTITUTE: brief description of the actual core gameplay loop — two-player, with a flag/goal-based objective and platform mechanics based on the file structure, but confirm the real loop here rather than relying on my guess]

## Tech Stack

**Client** — React, Redux, Socket.IO client
**Server** — Node.js, Socket.IO server

Real-time client-server state sync (player positions, game state, connection handling) implemented via Socket.IO over WebSocket transport.

## Structure

- `/client` — React/Redux frontend, real-time game state and rendering
- `/server` — Node.js server, Socket.IO connection handling and game logic

## Context

This project predates Dvor, the falling-block puzzle game currently in development at Studio Betonika, and shares no code with it. It's included here as evidence of hands-on real-time multiplayer architecture experience — Socket.IO/WebSocket communication, shared game state across clients — built prior to and informing Dvor's own Firebase-backed cross-platform leaderboard system.

Built in 2019, unmodified since except for repository reorganisation.
