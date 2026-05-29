## Tic Tac Toe

A beautiful, self-contained tic-tac-toe game built with vanilla HTML, CSS, and JavaScript.

### Features

- Play against an unbeatable AI (minimax algorithm)
- Animated red line drawn across winning tiles
- Persistent scoreboard (wins / losses / draws) saved in localStorage
- **Game start confirmation dialog** — "Would you like to play a game?" with Yes/No options (prevents accidental starts)
- Clean modern UI with smooth interactions
- Fully responsive — works great on desktop and mobile
- No build step, no dependencies, works completely offline

### How to Play

1. Open `index.html` in any modern browser (Chrome, Safari, Firefox, Edge)
2. A dialog will appear asking **"Would you like to play a game?"**
3. Click **Yes** to start — or **No** if you change your mind
4. Click any empty cell to place your **X**
5. The computer (**O**) will respond automatically using optimal play
6. First player to get three in a row wins!

### Running Locally

No installation required. Just open the file:

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

### Controls

- **Click** cells to make your move
- **New Game** button — triggers the confirmation dialog before starting a fresh game
- **Reset Scores** button — clear the win/loss/draw history
- Press **R** on your keyboard anytime to restart (also triggers the confirmation dialog)

### Tech Stack

- Pure HTML5 + CSS3 + JavaScript (ES6)
- No frameworks or build tools
- Google Fonts (Inter + Space Grotesk) for polish (gracefully falls back)

### Project Structure

```
tic-tac-toe/
└── index.html   # The complete game (HTML + CSS + JS)
```

---

Enjoy the game! ♠️

Created with ❤️ by [cashiny](https://github.com/cashiny)