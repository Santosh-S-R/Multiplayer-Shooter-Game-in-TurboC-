# Multiplayer Shooter Game (Turbo C++)

A retro-style two-player shooting game built using Turbo C++ graphics. This project was one of my earliest large-scale implementations, focusing on real-time interaction, basic physics, and file handling.

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
![Gameplay](./assets/gameplay.png)

- Real-time movement and shooting  
- Mouse-based aiming  
- Live defender life tracking  

---

### Game Over Screen
![Game Over](./assets/game-over.png)

- Displays the winner  
- Final score summary for both players  

---

### Player Details and Score Storage
![Player Details](./assets/player-details.png)

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

## Limitations

- Designed for Turbo C++ / DOS environment  
- Not compatible with modern compilers without modification  
- Uses legacy constructs such as `gets()` and `goto`  

---

## How to Run

You can run this project using an online Turbo C++ graphics compiler:

https://graphics-h-compiler.vercel.app/compiler

---

## Future Improvements

- Port to modern frameworks such as SFML or SDL  
- Improve graphics and UI  
- Add sound effects  
- Introduce AI opponent  
- Expand gameplay features  

---

## About the Project

This project was developed as an early exploration into game development, focusing on graphics programming, user input handling, and fundamental game mechanics.
