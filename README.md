# 🍄 Fraudio Brothers

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Canvas](https://img.shields.io/badge/Canvas_API-000000?style=for-the-badge&logo=html5&logoColor=white)

**Fraudio Brothers** is a classic-style 2D platformer developed entirely in Vanilla JavaScript and HTML5 Canvas. Designed with precise console-like mechanics and a retro aesthetic, the game offers a journey through 8 thematic worlds. 

This project was created with accessibility in mind for players of all ages (especially for kids), offering responsive touch controls and procedural audio generation, without relying on any external media files.

---

## ✨ Key Features

* **Advanced Platforming Physics:** 
  * **Coyote Time (150ms):** Allows jumping right after leaving a platform's edge, preventing unfair falls.
  * **Jump Buffer (150ms):** Registers jump inputs just before touching the ground to chain perfect jumps.
  * **Short Hop:** Variable jump height depending on how long the jump button is held.
* **Synthesized Audio Engine:** All music (randomized background melodies) and sound effects (jumps, coins, power-ups, damage) are generated in real-time using the **Web Audio API**. Zero external `.mp3` or `.wav` files are used.
* **8 Thematic Worlds:** Progressive level generation with color variations, floating platforms, pits, and different types of enemies (walkers, jumpers, flyers, and shooters).
* **Dynamic Power-Ups:** Particle systems, temporary invulnerability, and a "Satellite" mode that alters the music and color palette in real-time.
* **Responsive Design & Hybrid Controls:** Full keyboard support on desktop and multi-touch overlay virtual buttons that adapt to screen size on mobile devices.

---

## 🎮 Controls

| Action | Keyboard (Desktop) | Touch (Mobile) |
| :--- | :--- | :--- |
| **Move Left** | `Left Arrow` / `A` | On-screen ◄ button |
| **Move Right** | `Right Arrow` / `D` | On-screen ► button |
| **Jump** | `Up Arrow` / `W` / `Space` | On-screen ▲ button |

*(Note: Tapping anywhere on the screen while in the menus will start the game or advance to the next screen).*

---

## 🚀 Installation & Usage

Being built purely in HTML5 and JS, this game requires no Node.js dependencies, Webpack, or complex servers for basic development and execution.

1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/fraudio-brothers.git](https://github.com/your-username/fraudio-brothers.git)
