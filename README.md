# 🐟 Hungry Fish

**Name:** Mahir Shahriar Mahi
**Student ID:** 11230321436
**GitHub:** [Mahi1436](https://github.com/Mahi1436)
**Course:** Computer Graphics and Multimedia System Lab

## About the Game

Hungry Fish is a real-time underwater game drawn on an HTML5 canvas. You control a small fish: **eat the smaller green fish to grow bigger** and avoid the bigger red fish that can eat you. You have 3 lives, and the game gets faster every level. How high can you score?

## How to Play

| Control | Action |
|---|---|
| Mouse / touch | Your fish swims towards the pointer |
| `W` `A` `S` `D` or arrow keys | Swim up / left / down / right |
| `Enter` | Start / restart |
| `P` or `Space` | Pause / resume |
| `R` | Restart |
| `Esc` | Back to the menu |
| `M` | Sound on / off |

**Rules**
- 🟢 **Green fish** are smaller than you: touch them to eat them (**+10 points**) and grow a little.
- 🔴 **Red angry fish** are bigger than you: touching one costs **1 life**.
- You have **3 lives**. When they are gone, the game is over.
- Every **100 points** you reach a new level and the fish swim faster.

## Features

- Real-time graphics drawn on an HTML5 **canvas** (animated ocean, light rays, swaying seaweed, rising bubbles)
- Player-controlled fish (mouse, touch and keyboard)
- **Moving objects:** enemy fish swim across the screen with a wavy motion and wiggling tails
- **Collision detection** (circle vs circle) between the player and every fish
- **Eat-or-be-eaten rule:** fish change colour (green / red) depending on whether they are smaller or bigger than you
- Player grows every time it eats a fish
- Live **score**, **level**, **best score** and **lives** (fish icons) on screen
- **Levels:** faster fish, faster spawning and more dangerous fish as you score
- 3 lives, with a short protection time (blinking) and screen shake after being hit
- **Game-over screen** showing the final score, fish eaten and high score
- **High score saved** in the browser (`localStorage`)
- **Start menu**, **pause**, **restart** and **quit to menu**
- **Sound effects** (Web Audio API) with a sound on/off toggle
- Particle effects when eating and floating "+10" popups
- Fully responsive: works on desktop and mobile (touch controls)
- Single-file project, no libraries or installation needed

## Screenshots
- Screenshots will be attached later when the game will be fully developed

## Technologies Used

- **HTML5:** `<canvas>` element for the game area, buttons and information cards
- **CSS3:** custom properties (`:root`), Grid/Flexbox layout and responsive media queries
- **JavaScript (ES6+):** Canvas 2D API, game loop with `requestAnimationFrame`, collision detection, Web Audio API and `localStorage`

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Mahi1436/Hungry-Fish.git
   ```
2. Open the project folder:
   ```bash
   cd Hungry-Fish
   ```
3. Double-click `index.html` to play in any modern browser (Chrome, Edge, Firefox, Safari), or use the **Live Server** extension in VS Code.

## Project Structure

```
Hungry-Fish/
│
├── index.html        # Complete game (HTML, CSS and JavaScript)
├── README.md         # Project documentation
└── screenshots/      # Screenshots used in this README
```

## License

This project is open-source and created for educational purposes by Mahir Shahriar Mahi. Feel free to explore, modify and use it!
