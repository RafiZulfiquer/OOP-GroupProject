# Goblin Slayer

A wave-based survival game built with C++ and SFML, featuring multiple character classes, progressive difficulty, and a competitive leaderboard system.

## 🎮 Game Overview

Goblin Slayer is an action-packed survival game where players battle through increasingly difficult waves of goblin enemies. Choose your class, level up your character, and climb the leaderboard as you fight to survive!

### Key Features

- **Three Unique Classes**: Warrior, Wizard, and Rogue, each with distinct playstyles and abilities
- **Class Evolution System**: Unlock powerful upgraded classes at level 10
- **Dynamic Wave System**: Face progressively stronger enemies with boss encounters every 10 waves
- **Experience & Leveling**: Gain XP from kills to level up and enhance your stats
- **Persistent Leaderboard**: Track top scores across sessions
- **Multiple Enemy Types**: Regular Goblins, armored Goblin Brutes, and powerful Goblin Lords

## 🕹️ How to Play

### Controls
- **WASD**: Move your character
- **Left Click**: Attack (aim with mouse)
- **ESC**: Pause game / Return to menu

### Classes

**Warrior**
- High durability melee fighter
- Evolves into **Knight** at level 10 with charge attack ability

**Wizard**
- Ranged spellcaster with mana-based attacks
- Evolves into **Archmage** at level 10 with devastating meteor ability

**Rogue**
- Fast attacker with critical hit chance
- Evolves into **Assassin** at level 10 with invisibility and bonus damage

### Enemy Types

- **Goblin**: Basic enemy with standard stats
- **Goblin Brute**: Armored tank with damage reduction (appears from wave 5)
- **Goblin Lord**: Boss enemy that summons minions (appears every 10 waves)

## 🛠️ Technical Details

### Built With
- **C++17**: Core game logic and systems
- **SFML 2.5+**: Graphics, window management, and input handling
- **Object-Oriented Design**: Inheritance-based class system for extensibility

### Architecture Highlights

- **Entity-Component Pattern**: Modular entity system for players and enemies
- **Strategy Pattern**: Flexible attack system supporting multiple attack types
- **State Machine**: Clean menu and game state management
- **Environment System**: Collision detection and entity lifecycle management

### Key Components

- **Player Classes**: Base `Player` class with derived `Warrior`, `Wizard`, and `Rogue`
- **Enemy AI**: Movement, attack patterns, and wave-based spawning
- **Attack System**: Projectile, melee, and special attack implementations
- **Wave Manager**: Exponential difficulty scaling with boss encounters
- **Leaderboard**: File-based persistence for high scores

## 📦 Installation & Setup

### Prerequisites
- C++17 compatible compiler (GCC, Clang, MSVC)
- SFML 2.5 or higher
- CMake 3.10+ (recommended)

### Build Instructions
```bash
# Clone the repository
git clone https://github.com/yourusername/goblin-slayer.git
cd goblin-slayer

# Compile (example using g++)
g++ -std=c++17 *.cpp -o GoblinSlayer -lsfml-graphics -lsfml-window -lsfml-system

# Run the game
./GoblinSlayer
```

**Note**: Ensure `arial.ttf` font file is in the same directory as the executable for proper text rendering.

## 🤝 Contributors

This project was developed collaboratively by:
- [@a1211368](https://github.com/a1211368)
- [@a1969929](https://github.com/a1969929)

## 📈 Future Enhancements

- Additional character classes and evolution paths
- Power-up system and item drops
- Sound effects and background music
- Multiplayer co-op mode
- Steam leaderboard integration

## 📄 License

This project is available for educational and portfolio purposes. Please contact contributors for usage rights.

## 🎯 Acknowledgments

Built as a demonstration of object-oriented programming principles, game development patterns, and C++ proficiency with SFML.

---

*Survive the waves. Defeat the Goblin Lords. Claim your place on the leaderboard!*
Rogue critical hits
Enemy swarm behavior
Player death scenarios
Exception handling across systems
Memory management
