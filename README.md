# 🎮 Python Arcade Shooter Game
## 📝 Summary
This project demonstrates how to create a classic arcade-style aircraft shooter game using **Python** and the **Pygame** library. The goal is to provide an exciting aerial combat experience while teaching fundamental game development concepts such as event handling, collision detection, and game logic structuring.

## ✈️ Game Features
* Player-Controlled Aircraft  
Navigate using keyboard arrow keys; shoot using the spacebar.
* Dynamic Environment
        * Scrolling backgrounds
        * Randomly generated enemy rocks
        * Bullet mechanics and collisions
        * Scoring system & HP (health point) system
        * Explosions and sound effects
* Difficulty Scaling  
The game gradually becomes harder as time progresses, enhancing player engagement and challenge.   
## 🌐 Environment Setup
```
import pygame
import random
import os
```
* Python 3.x
* Pygame library (pip install pygame)
## 🚀 Usage Instructions  
1. Run the game script:
```
python shooter_game.py
```
2. Controls:
* ← ↑ ↓ → — Move the aircraft
* Spacebar — Fire bullets  
![image](https://github.com/DennisHsu716/STG.github.io/blob/main/img/1.png)


Use direction key to control the plane, and use space key to shoot.

![image](https://github.com/DennisHsu716/STG.github.io/blob/main/img/1.gif)

## 📁 Folder Structure
```
shooter_game/
├── assets/               # images and sounds
├── shooter_game.py       # main game logic
└── README.md             # project description
```

## 🧠 Skills Developed
* Event-driven programming
* Real-time game loop design
* Sprite animation & movement
* Collision detection
* Sound and visual effects integration
* Score tracking and difficulty progression

## 🔭 Future Plans
* Add different enemy types and boss battles
* Power-ups (e.g., double bullets, shields)
* Save/load game progress
* Create game menu and pause/resume system
* Leaderboard functionality using files or online database
* Polish UI with enhanced effects and sound

