# 👻 Ghost Dodger

**Ghost Dodger** is a fast-paced, highly addictive web-based survival game built entirely with HTML5 Canvas, CSS, and Vanilla JavaScript. Your goal is simple but challenging: survive as long as possible by dodging the relentless rain of falling ghosts! 

Whether you're looking for a quick break or aiming to beat your personal best, Ghost Dodger delivers instant fun directly in your browser.

---

## 🏆 Why Ghost Dodger? (Pros vs. Existing Systems)

When compared to other browser games or heavy standalone titles, Ghost Dodger stands out for its simplicity, speed, and privacy:

- **Zero Dependencies & Zero Installation:** Unlike games built with heavy engines (Unity, Unreal) or complex JS frameworks (React, Phaser), Ghost Dodger is purely Vanilla. No `npm install`, no complex build steps, and no downloading large executables.
- **Blazing Fast Load Times:** With a microscopic footprint (under 10KB total), the game loads instantly on any internet connection. No loading screens, just instant gameplay.
- **Privacy First (Local Storage):** Your high scores are saved locally on your device. There are no accounts to create, no servers tracking your behavior, and absolutely no intrusive ads or microtransactions.
- **Clean & Educational Codebase:** The entire game runs from a single HTML file with elegantly structured JavaScript. It serves as a perfect learning resource for developers wanting to understand game loops, collision detection, and HTML5 Canvas mechanics.
- **Cross-Platform Accessibility:** Works seamlessly on any modern operating system (Windows, macOS, Linux) with a web browser.

---

## ✨ Key Features

- **Dynamic Difficulty Scaling:** The challenge ramps up dynamically. Every 5 seconds you survive, the game speed increases, ensuring that the gameplay remains constantly engaging and tests your reflexes.
- **Interactive Powerup System:** It's not just about dodging! Strategic items drop from the sky to help you survive:
  - 🛡️ **Shield (Invincibility):** Grants temporary immunity against ghost collisions for 5 seconds.
  - 🐢 **Slow Motion:** Temporarily reduces the speed of the falling ghosts for 5 seconds, giving you a chance to reposition.
- **Multiple Selectable Difficulties:** Choose between Easy, Medium, and Hard right from the start menu to tailor the initial ghost speed to your skill level.
- **Character Customization:** Personalize your playthrough by choosing from fun emoji-based skins: Play as a Wizard (🧙‍♂️), Vampire (🧛‍♂️), or Zombie (🧟‍♂️).
- **Persistent High Score Tracking:** Your best survival time is permanently recorded in your browser's local storage, giving you a continuous target to beat.
- **Seamless Pause Functionality:** Need a quick break? Hit the `Esc` key to pause the action without losing your progress, complete with a clean pause overlay.

---

## 🎮 How to Play

- **Movement:** Use the **Left** (⬅️) and **Right** (➡️) arrow keys to move your character horizontally across the screen.
- **Objective:** Avoid the falling ghosts (👾). If a ghost touches you, it's Game Over!
- **Powerups:** Intercept the falling powerups (🛡️ or 🐢) to gain temporary advantages.
- **Pause:** Press the **Escape (Esc)** key at any point to pause or unpause the game.

---

## 🚀 Getting Started

Getting the game running on your machine is incredibly simple. 

1. **Clone or Download** this repository to your local machine.
2. Navigate to the project folder.
3. Simply **double-click** the `Index.html` file to open it in your preferred modern web browser (Chrome, Firefox, Edge, Safari).
4. *That's it!* Select your difficulty, choose a skin, and start dodging!

---

## 🛠️ Technologies Used

Ghost Dodger was crafted to be as lightweight and native as possible:

- **HTML5 (Canvas API):** Provides the foundational structure and the high-performance rendering context for the game loop and sprites.
- **CSS3:** Used for the sleek UI overlays, modern gradients, typography, and smooth CSS animations (like the fade-in screens).
- **Vanilla JavaScript (ES6+):** Drives the core game loop, entity management, collision detection algorithms, event handling, and HTML5 `localStorage` integration.

---
## 🤝 Contributing

This project is open-source and highly extensible! If you want to add new powerups, more enemy types, sound effects, or mobile touch controls, feel free to fork the repository and submit a pull request.
