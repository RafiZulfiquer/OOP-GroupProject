# Goblin Slayer

<p align="center">
  <img src="assets/banner.png" alt="Goblin Slayer Banner" width="800">
</p>

<p align="center">
  <b>A C++ & SFML wave-based survival game featuring evolving classes, fast combat, and competitive leaderboards.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C++-17-blue.svg">
  <img src="https://img.shields.io/badge/SFML-2.5+-brightgreen.svg">
  <img src="https://img.shields.io/badge/License-Custom-lightgrey.svg">
  <img src="https://img.shields.io/badge/Platform-PC-orange.svg">
</p>

---

## 🎮 Gameplay Preview

<p align="center">
  <img src="assets/gameplay.gif" alt="Gameplay GIF" width="600">
</p>

> *(Optional — add a gameplay GIF to `assets/gameplay.gif` to display it here.)*

---

## 🎮 Game Overview

**Goblin Slayer** is an action-packed survival experience where you battle through increasingly difficult waves of goblins. Choose your class, evolve into powerful forms, unleash special abilities, and climb the leaderboard.

---

## ✨ Key Features

- **Three Unique Classes** — Warrior, Wizard, and Rogue  
- **Class Evolutions at Level 10** — Knight, Archmage, Assassin  
- **Dynamic Wave Scaling** — Bosses every 10 waves  
- **XP & Leveling System** — Increase health, damage, speed  
- **Persistent Leaderboard** — Scores saved locally  
- **Multiple Enemy Types** — Goblins, Brutes, Lords, summons  

---

## 🕹️ How to Play

### Controls
| Action | Key |
|-------|------|
| Move | **W, A, S, D** |
| Attack | **Left Mouse Button** |
| Aim | **Mouse** |
| Pause / Menu | **ESC** |

---

## 🧙 Classes & Evolutions

### 🛡️ Warrior → Knight (Level 10)
- Tanky melee fighter  
- Evolution ability: **Charge Attack**

### 🔥 Wizard → Archmage (Level 10)
- Ranged spellcaster  
- Evolution ability: **Meteor Strike**

### 🗡️ Rogue → Assassin (Level 10)
- Fast, high crit chance  
- Evolution ability: **Invisibility + Bonus Damage**

---

## 👺 Enemy Types

- **Goblin** — Standard melee enemy  
- **Goblin Brute** — Armored brute that reduces incoming damage (from Wave 5)  
- **Goblin Lord** — Summons minions; boss every 10 waves  

---

## 🛠️ Technical Details

### Built With
- **C++17**
- **SFML 2.5+**
- **CMake**
- **Object-Oriented Architecture**

### Architecture Highlights
- **Entity–Component Design** for modularity  
- **Strategy Pattern** for attack types  
- **Finite State Machine** for menu/game transitions  
- **Collision System** for environment & entities  
- **File-Based Leaderboard System** for persistence  

### Core Components
- Player class hierarchy  
- Enemy AI & pathfinding behavior  
- Projectile + melee combat  
- Wave Manager with increasing difficulty  
- Leaderboard tracking  

---

## 📦 Installation & Setup

### Prerequisites
- C++17 compiler  
- SFML **2.5+**  
- CMake **3.10+** (recommended)

### Build Instructions
```bash
# Clone the repository
git clone https://github.com/yourusername/goblin-slayer.git
cd goblin-slayer

# Compile (using g++)
g++ -std=c++17 *.cpp -o GoblinSlayer -lsfml-graphics -lsfml-window -lsfml-system

# Run the game
./GoblinSlayer
