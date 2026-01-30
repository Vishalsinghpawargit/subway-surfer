# 🏃‍♂️ AI-Architected Subway Surfers Clone
### A 3D Web Experiment using Three.js and the "Big Three" AI Models

![Three.js](https://img.shields.io/badge/Three.js-Black?style=for-the-badge&logo=three.js)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

This project is a 3D "Endless Runner" built from scratch using **Three.js**. The core objective was to test the coding capabilities of **ChatGPT (OpenAI)**, **Gemini (Google)**, and **Claude (Anthropic)** to see which model could best handle complex game loops, 3D physics, and UI integration.

## 🧠 The Experiment
As a developer and gaming enthusiast, I wanted to see if a non-Unity expert could build a functional 3D game using only web technologies and AI co-pilots. I used the same base prompt for all three models: 

> *"Build a Subway Surfers clone using HTML, CSS, and Three.js with lane-switching, obstacles, and a score system."*

### The Verdicts:

| Model | Strength | Weakness | Result |
| :--- | :--- | :--- | :--- |
| **ChatGPT** | Logic Snippets | Full Game Loop | Great for isolated functions, but missed the "Game Over" state. |
| **Gemini** | Spatial Awareness | UI Optimization | Strong grasp of the 3D environment and big-picture mechanics. |
| **Claude** | **Overall Execution** | N/A | **The Winner.** Polished UI and perfect controls right out of the box. |

---

## 🚀 Features
* **Procedural Generation:** Endless track and obstacle spawning.
* **Lane Switching:** Smooth character movement across 3 lanes using `Lerp` for transitions.
* **Responsive UI:** A fully functional start menu and game-over screen.
* **Collision Detection:** Real-time bounding box calculations for high-speed gameplay.

---

## 🛠️ Technical Stack
* **Engine:** [Three.js](https://threejs.org/) (WebGL)
* **Language:** JavaScript (ES6+)
* **Styling:** CSS3 for the game overlay and HUD.
* **Architecture:** AI-assisted prompt engineering.

---

## 📖 Key Takeaways
The secret isn't just the AI you use—it's the **Prompt Engineering** and **Technical Oversight**. 

1.  **AI is a Co-pilot:** It builds based on assumptions unless you act as the Architect.
2.  **Context is King:** Claude excelled at keeping the global state of the game in mind, whereas others struggled with the continuity of the game loop.
3.  **The "Human" Touch:** While AI generated 90% of the code, fine-tuning the physics and "feel" of the movement required human intuition and steering.

---

## 🎮 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/subway-surfers-ai.git](https://github.com/your-username/subway-surfers-ai.git)
    ```
2.  **Navigate to the folder:**
    ```bash
    cd subway-surfers-ai
    ```
3.  **Launch the game:**
    Open `index.html` in your browser (preferably via a Live Server extension to ensure all Three.js assets load correctly).

---

## 🤝 Contributing
Since this was an experiment in AI architecture, I’d love to see how others "steer" the code. Feel free to fork, add new obstacles, or improve the shaders!

---
*Created by a developer obsessed with how games are built.*