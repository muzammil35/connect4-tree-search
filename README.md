# 🟡 Connect4-Tree-Search

A **Connect 4 game with a playable web interface** and a **tree-search AI opponent** built in Go.

Play the game in your browser and compete against an algorithm that uses game-tree search (Negamax with α-β pruning) to find strong moves.

---

## Features

-  **Interactive Web UI** — Play Connect 4 in the browser.
-  **AI Opponent** — A game solver using **Negamax with alpha-beta pruning**.
-  **REST API** — Server endpoints power the UI and allow external clients to integrate.
-  **Written in Go** — Clean, fast implementation with a small footprint.

---

##  Demo

Try the live version: [Play Online](https://connect4-app-768895558000.northamerica-northeast1.run.app/)

---

##  Project Structure

├── main.go # server entrypoint
├── solver/ # game logic & tree search algorithm
├── templates/ # HTML templates for UI
├── static/ # bundled CSS/JS assets
├── Dockerfile # container config
├── go.mod # Go modules
└── README.md # this file

## How the player generates moves

The plsyer uses a game-tree search algorithm (Negamax with alpha-beta pruning) — a common approach in board games to explore possible future board states and pick the best move. This approach is depth-limited with pruning to reduce computation while still finding strong moves.





