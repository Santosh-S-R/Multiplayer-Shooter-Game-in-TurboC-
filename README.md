# Multiplayer Shooter Game (Turbo C++)

A retro-style two-player shooting game built using Turbo C++ graphics. This project was one of my earliest large-scale implementations, focusing on real-time interaction, basic physics, and file handling.

---

## How to Run

You can run this project using an online Turbo C++ graphics compiler:

https://graphics-h-compiler.vercel.app/compiler

---

## Gameplay Overview

This is a local multiplayer game with two roles:

- **Attacker** — Moves using `W A S D` and shoots using the mouse  
- **Defender** — Moves using `I J K L` to dodge incoming shots  

Objective:
- The attacker attempts to hit the defender using limited shots  
- The defender aims to survive as long as possible  

---

## Screenshots

### Gameplay
![Gameplay](./gameplay.png)

- Real-time movement and shooting  
- Mouse-based aiming  
- Live defender life tracking  

---

### Instructions Screen
![Instructions](./instructions.png)

- Displays game rules and controls  
- Explains attacker vs defender roles  
- Shows win conditions clearly  

---

### Game Over Screen
![Game Over](./game-over.png)

- Displays the winner  
- Final score summary for both players  

---

### Player Details and Score Storage
![Player Details](./player-details.png)

- Player name input  
- Score calculation  
- Persistent storage using file handling  
---

## Features

- Real-time two-player gameplay  
- Combined keyboard and mouse controls  
- Bullet trajectory using mathematical calculations  
- Collision detection system  
- Life-based gameplay mechanics  
- File-based score saving (`score.txt`)  
- Scoreboard display functionality  

---

## Technical Details

Built using:
- `graphics.h` for rendering  
- `dos.h` for mouse interrupt handling  
- `conio.h` for keyboard input  

Concepts implemented:
- Game loop design  
- Basic physics (trajectory and collision)  
- Binary file handling  

---

## Some parts that could be improved

- Designed for Turbo C++ / DOS environment  
- Not compatible with modern compilers without modification  
- Uses legacy constructs such as `gets()` and `goto`  

---

---

## About the Project

This project was developed as an early exploration into game development, focusing on graphics programming, user input handling, and fundamental game mechanics.
