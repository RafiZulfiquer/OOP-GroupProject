# Goblin Slayer

A **C++ & SFML wave-based survival game** featuring multiple character classes, class evolutions, progressive difficulty, and a persistent leaderboard system.

---

## 🎮 Game Overview

**Goblin Slayer** is an action-packed survival game where you fight through endlessly escalating waves of goblins. Level up, evolve your class into stronger forms, unlock special abilities, and climb the leaderboard.

---

## ✨ Key Features

- **Three Unique Classes** — Warrior, Wizard, Rogue  
- **Class Evolutions at Level 10** — Knight, Archmage, Assassin  
- **Dynamic Wave System** — Increasing difficulty with bosses every 10 waves  
- **XP & Leveling System** — Boost stats and unlock abilities  
- **Persistent Leaderboard** — Saves top scores across sessions  
- **Multiple Enemy Types** — Goblins, Brutes, Lords, and summoned minions  

---

## 🕹️ How to Play

### **Controls**
| Action | Key |
|--------|------|
| Move | **W, A, S, D** |
| Attack | **Left Mouse Button** |
| Aim | **Mouse** |
| Pause / Menu | **ESC** |

---

## 🧙 Classes & Evolutions

### 🛡️ Warrior → Knight (Level 10)
- High durability  
- Evolution ability: **Charge Attack**

### 🔥 Wizard → Archmage (Level 10)
- Ranged, mana-based combat  
- Evolution ability: **Meteor Strike**

### 🗡️ Rogue → Assassin (Level 10)
- Agile, high critical hit chance  
- Evolution ability: **Invisibility + Bonus Damage**

---

## 👺 Enemy Types

- **Goblin** — Standard enemy  
- **Goblin Brute** — Armored brute with reduced damage taken (from Wave 5)  
- **Goblin Lord** — Boss enemy that summons minions (every 10 waves)  

---

## 🛠️ Technical Details

### **Built With**
- **C++17**
- **SFML 2.5+**
- **CMake 3.10+**
- **Object-Oriented Architecture**

### **Architecture Highlights**
- **Entity–Component Design** for modular entities  
- **Strategy Pattern** for attacks  
- **Finite State Machine** for menus and states  
- **Collision & Environment System** for interactions  
- **Persistent Leaderboard** using file storage  

### **Core Modules**
- Player class hierarchy (base + 3 classes + 3 evolutions)  
- Enemy AI (movement, targeting, spawning logic)  
- Combat System (melee, projectiles, abilities)  
- Wave Manager (difficulty scaling + bosses)  
- Leaderboard system  

---

## 📦 Installation & Setup

### **Prerequisites**
- C++17 compiler (GCC, Clang, or MSVC)  
- SFML **2.5 or higher**  
- CMake **3.10+** (recommended)

### **Build Instructions**
```bash
# Clone the repository
git clone https://github.com/yourusername/goblin-slayer.git
cd goblin-slayer

# Compile (using g++)
g++ -std=c++17 *.cpp -o GoblinSlayer -lsfml-graphics -lsfml-window -lsfml-system

Contributors

This project was developed collaboratively by:
@a1211368
https://github.com/a1211368
@a1969929
https://github.com/a1969929

# Run the game
./GoblinSlayer
