# ✈️ Jet Fighter Multiplayer

A multiplayer arcade-style **Jet Fighter** game built using a client-server architecture. Two players connect to a central server and battle each other in real time.

## 🎮 Gameplay

- Two-player multiplayer game
- Real-time client-server communication
- Arcade-style jet fighter combat

## 📜 Rules

- Each player's objective is to **shoot down the opponent's jet**.
- Every successful hit awards **1 point**.
- The **first player to reach 5 points wins** the game.

## 🏗️ Project Structure

```
jet_fighter_multiplayer/
├── Server/
├── Client/
└── README.md
```

- **Server** – Handles game state, player connections, and communication.
- **Client** – Runs the game interface for each player.

## 🚀 Running the Game

### 1. Start the Server

Run the server application first.

**Server Port:** `8200`

### 2. Start the Clients

Launch the client application on two different machines (or two instances on the same machine) and connect them to the server.

## 🛠️ Features

- Real-time multiplayer gameplay
- Client-server architecture
- Score tracking
- Win detection
- Smooth arcade-style controls

## 🏆 Winning Condition

🎯 The first player to score **5 points** wins the match.
