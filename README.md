# thing-game
A fast-paced, wave-based 3D survival FPS built in a single HTML file using Three.js. Protect the vaccine, survive the horde, and brave the Gauntlet.
# 🧟‍♂️ THING HUNTER

**Thing Hunter** is a tense, fast-paced, wave-based survival First-Person Shooter (FPS) built entirely in a single HTML file using the **Three.js** library. 

You are trapped in a dark, grid-based arena. At the exact center of the room lies a fragile vaccine. When the countdown begins, doors open on all four sides, and the horde swarms in. Your mission: Survive the wave, protect the vaccine at all costs, and compete for the fastest clear time on the server leaderboard.

## 🎮 Play the Game
*(Note: If you host this on GitHub Pages, you can put the live link here! Example: [Play Thing Hunter Here](https://yourusername.github.io/thing-hunter))*

## ✨ Core Features

* **The Gauntlet (4 Levels of Scaling Difficulty):** Progress through increasingly difficult waves with larger arenas, faster enemies, and synchronized, coordinated spawning logic.
* **Dynamic Spawning System:** Maintains constant pressure with a "Max Active" zombie cap, keeping the arena filled with action without overwhelming browser memory.
* **Advanced Zombie AI:** Enemies naturally track the central vaccine but feature a dynamic aggro system. If you enter their 50 sq ft proximity zone, there is a 50% chance they will drop focus on the vaccine and hunt you instead.
* **Modern Gunplay:** Wield an auto-fire AK-47 with an Aim Down Sights (ADS) Red Dot Scope mechanic for precision headshots. Use AoE grenades and medkits to manage the horde.
* **Local Multiplayer (Pass-and-Play):** Compete with friends locally. Take turns running the Gauntlet and track who cleared levels the fastest on the built-in Session Leaderboard.
* **Risk & Reward Penalty:** Locked into the Gauntlet? You can hit the "Abort Mission" button between rounds, but taking the coward's way out will instantly strip 50% of your total score.

## ⌨️ Controls

* **W, A, S, D:** Move
* **Mouse:** Look / Aim
* **Left-Click (Hold):** Auto-Fire
* **Right-Click (Hold):** Aim Down Sights (ADS / Red Dot Scope)
* **R:** Reload Weapon
* **G:** Toggle Grenade Mode (Click to throw)
* **F:** Use Medkit
* **ESC:** Pause Game / Release Mouse

## 🚀 Installation & Setup

Because Thing Hunter is built as a lightweight, purely client-side application, installation is incredibly simple.

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/thing-hunter.git](https://github.com/yourusername/thing-hunter.git)
Navigate to the project folder.

Open index.html directly in any modern web browser (Chrome, Edge, Firefox, or Safari). No local server is strictly required!

🛠️ Technologies Used
HTML5 / CSS3: For the UI, minimalistic HUD, menus, and layout.

JavaScript (ES6+): For core game logic, AI behavior, and state management.

Three.js (r128): For 3D rendering, lighting, raycasting (hit detection), and particle systems.
