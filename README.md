# 💡 The Impossible Lightbulb

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://pankajtiwari-art.github.io/The-Impossible-Lightbulb/)
[![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-blue.svg)](https://opensource.org/licenses/MPL-2.0)

A highly interactive, state-driven front-end animation inspired by the classic "Useless Box" concept. Pull the light cord to turn on the bulb, but be prepared—a grumpy bear is trying to sleep, and he will come out to turn it off! 🐻

The more you turn on the light, the angrier the bear gets. Watch as the animations and interactions progressively change based on the bear's "anger level."

## ✨ Features

* **Interactive Draggable Cord:** Physics-like interaction using GSAP's Draggable plugin. Pull the cord down to toggle the light.
* **Progressive State Management:** The JavaScript logic tracks an `ANGER` state. With each toggle, the bear's reactions become faster and more aggressive (e.g., slamming the door, showing angry eyebrows).
* **Dynamic Lighting Engine:** Utilizes CSS Custom Properties (`--on`, `--bg`, `--shine`) to smoothly transition the entire scene's lighting and background colors between ON and OFF states.
* **Advanced SVG Morphing:** Employs GSAP's MorphSVGPlugin for fluid, organic animations of the bear and the environment.
* **Immersive Audio:** Features synchronized sound effects, including mechanical clicks, door opening/closing, and bear groans, adding depth to the user experience.
* **3D Transforms:** The door utilizes CSS `preserve-3d` and `rotateY` for a realistic 3D swinging effect.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure and heavy use of inline SVGs for rendering the complex scene.
* **CSS3:** Advanced styling, CSS variables for dynamic state changes, and 3D transforms.
* **JavaScript (ES6+):** Core logic, state management, and event handling.
* **GSAP (GreenSock Animation Platform):** * `gsap.timeline()` for sequencing complex animations.
  * `MorphSVGPlugin` for SVG path morphing.
  * `Draggable` for the interactive pull cord.

## 🚀 Play with it (Live Demo)

Check out the live interactive version here: **[The Impossible Lightbulb](https://pankajtiwari-art.github.io/The-Impossible-Lightbulb/)**

## 💻 Local Setup

If you want to run this project locally or modify the code:

1. Clone this repository:
   git clone https://github.com/pankajtiwari-art/The-Impossible-Lightbulb.git

2. Navigate to the project directory:
   cd The-Impossible-Lightbulb

3. Open `index.html` in your favorite web browser. No build tools or servers are required!

## 📂 File Structure

* `index.html`: Contains the SVG graphics and overall structure.
* `style.css`: Houses all the styling, including the dynamic CSS variables.
* `script.js`: Contains the GSAP animation timelines, audio handling, and state logic.

## 📜 License

This project is licensed under the **Mozilla Public License 2.0 (MPL-2.0)**. 

You are free to use, modify, and distribute the code, provided that any modifications to the files under this license are also made available under the MPL 2.0. For more details, see the `LICENSE` file or read about it [here](https://opensource.org/licenses/MPL-2.0).

---
*Created with logic, code, and a bit of mischief by [Pankaj Tiwari](https://github.com/pankajtiwari-art).*
