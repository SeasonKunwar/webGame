# 🧩 Maze Adventure Game

A browser-based maze game inspired by classic arcade gameplay.  
Collect fruits, avoid enemies, survive longer, and achieve the highest score.

---

## 🎮 Game Overview

Maze Adventure is a grid-based JavaScript game where the player navigates through a maze collecting fruits while avoiding roaming enemies.

The game features:

- Player movement using keyboard or on-screen controls
- Enemy AI movement
- Score system
- Health system
- Level progression
- Leaderboard saved using LocalStorage
- Healing fruit mechanics

---

## 🕹️ Gameplay

### Objective
- Collect all cherries to clear the level.
- Avoid enemies.
- Survive as long as possible and score high.

### Controls

Keyboard:

- `↑` Move Up
- `↓` Move Down
- `←` Move Left
- `→` Move Right

Mobile:

- Use on-screen arrow buttons.

---

## 🍒 Game Items

### Cherry
- Main collectible
- Increases score by **+1**
- Required to complete the level

### Apple
- Healing fruit
- Restores **+1 life**
- Available starting from Level 1
- Maximum lives: **5**

---

## 👾 Enemies
- Move randomly inside the maze
- Collision with player removes one life
- Enemy count increases every level

---

## ❤️ Lives System
- Player starts with **3 lives**
- Apples can heal the player
- Game ends when lives reach **0**

---

## 🏆 Leaderboard
- Top 5 scores are saved locally
- Stored using browser LocalStorage
- Automatically updates after finishing a level

---

## 📈 Level Progression
Each new level:

- Adds more enemies
- Adds more apples
- Resets cherries
- Increases difficulty

---

## 🧱 Project Structure
│
├── index.html
├── style.css
├── script.js
│
└── img/
├── player.png
├── enemy.png
├── cherry.png
└── apple.png


---

## 🛠️ Technologies Used

- HTML5
- CSS3 Grid Layout
- Vanilla JavaScript (ES6)
- LocalStorage API

---

