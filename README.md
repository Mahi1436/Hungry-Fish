# ✕○ Tic-Tac-Toe Ultimate Edition

A modern, responsive, and feature-rich **Tic-Tac-Toe** web game built with pure **HTML5**, **CSS3**, and **Vanilla JavaScript**. Designed with a sleek UI/UX focus, this project was developed as part of a **Graphics Design & Web Development** course.

## ✨ Key Features

* **🎮 Multiple Game Modes:**

  * **Player vs Player (PvP):** Play locally with a friend on the same device.

  * **Player vs AI (PvAI):** Challenge **Nova AI** across three difficulty levels (**Easy**, **Medium**, and **Hard**).

  * **AI vs AI (AIvAI):** Watch two AI agents compete against each other automatically.

* **🧠 Smart AI Engine:**

  * **Easy:** Makes randomized moves for casual play.

  * **Medium:** Uses strategic heuristics (winning moves, blocking opponent, center/corner control).

  * **Hard:** Powered by the **Minimax Algorithm**, making the AI virtually unbeatable.

* **🎨 Modern UI & Theme Customization:**

  * Seamless toggle between **Dark Mode** and **Light Mode**.

  * Custom player name inputs for personalized gameplay.

  * Smooth CSS transitions, glowing neon accents, and celebratory **Confetti Animations** upon winning.

* **📊 Real-Time Statistics & Match History:**

  * Tracks total games played, X win rate percentage, best winning streak, and move counts.

  * Keeps a log of recent completed matches using browser `localStorage` so data persists across sessions.

* **🔊 Interactive Controls & Audio:**

  * Built-in synthesized sound effects using the **Web Audio API** (no external audio files required).

  * **Undo Move** functionality to revert mistakes.

  * Instant round restart and score reset options.

* **📱 Fully Responsive Design:**

  * Optimized for desktop, tablet, and mobile viewports using CSS Grid and Flexbox.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure and accessible ARIA attributes.

* **CSS3:** Custom CSS Variables (`:root`), Grid/Flexbox layouts, keyframe animations, and responsive media queries.

* **JavaScript (ES6+):** DOM manipulation, game state management, Minimax AI algorithm, Web Audio API, and `localStorage` integration.

## 🚀 How to Run Locally

Since this project is built as a self-contained single-file web application, no external dependencies or build tools are required.

1. **Clone or Download the Repository:**

   ```
   git clone https://github.com/your-username/tic-tac-toe-ultimate.git
   
   ```

2. **Navigate to the Project Folder:**

   ```
   cd tic-tac-toe-ultimate
   
   ```

3. **Launch the Game:**

   * Simply **double-click** on the `index.html` file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).

   * *Optional:* Open the folder in **VS Code** and run it using the **Live Server** extension.

## 📂 Project Structure

```
tic-tac-toe-ultimate/
│
├── index.html      # Complete game (HTML structure, CSS styling, and JS logic)
└── README.md       # Project documentation

```

## 🎓 Academic Context

* **Course:** Graphics Design

* **Project Focus:** Visual hierarchy, color theory (dark/light palettes), responsive grid layout, interactive micro-animations, and clean user interface design.

## 📝 License

This project is open-source and created for educational purposes. Feel free to explore, modify, and use it!