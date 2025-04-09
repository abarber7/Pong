# 🕹️ Pong – Remake in Lua with Love2D

**Developer:** Antonio Barber  
**Framework:** [LÖVE2D](https://love2d.org/)  
**Language:** Lua  
**Repository:** [Pong](https://github.com/abarber7/Pong)

---

## 🎮 Project Overview

This project is a faithful remake of the classic arcade game **Pong**, developed using the **Love2D** framework and written in **Lua**. The game replicates the fast-paced paddle action of the original, adding a few modern improvements in structure and polish while maintaining the retro feel.

The project was built to demonstrate:

- Familiarity with game loops and state machines  
- Collision detection and basic physics  
- Use of Love2D for rendering, input handling, and sound  
- Modular Lua programming for game development

---

## 📦 Features

✅ Classic 2D Pong mechanics  
✅ Smooth player and AI paddle movement  
✅ Ball bounce logic and collision physics  
✅ Score tracking and win condition  
✅ Simple game state management (start, play, win)  
✅ Sound effects for paddle hits, scoring, and wall collisions  
✅ Retro-inspired visual style

---

## 🕹️ Controls

| Action         | Key            |
|----------------|----------------|
| Move Paddle 1  | `W` / `S`      |
| Move Paddle 2  | `Up` / `Down`  |
| Start Game     | `Enter` / `Return` |
| Quit Game      | `Escape`       |

---

## 🚀 Getting Started

### 🛠️ Requirements

- [LÖVE2D](https://love2d.org/) (version 11.3 or higher recommended)  
- Lua (installed automatically with Love2D)

Pong/
├── main.lua              # Entry point
├── Paddle.lua            # Paddle class
├── Ball.lua              # Ball class
├── StateMachine.lua      # Simple state machine implementation
├── states/
│   ├── StartState.lua    # Title/start menu logic
│   ├── PlayState.lua     # Main gameplay loop
│   ├── ServeState.lua    # Pre-serve state
│   └── VictoryState.lua  # Win screen state
└── assets/
    ├── fonts/            # Custom fonts
    └── sounds/           # Sound effects

