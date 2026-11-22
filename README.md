# Connect Four Game

A browser-based two-player Connect Four game built with HTML, CSS, and JavaScript.

## Features

- 6-row by 7-column game board
- Two-player gameplay with Red and Yellow pieces
- Automatic win detection in horizontal, vertical, and diagonal directions
- Draw detection when the board is full
- Restart button to start a new game
- Responsive layout for smaller screens

## How to Play

1. Open `index.html` in a web browser.
2. Player Red starts the game.
3. Select a column to drop your piece into the lowest available row.
4. Players alternate turns.
5. The first player to connect four pieces horizontally, vertically, or diagonally wins.
6. Select **Restart Game** to play again.

## Run Locally

From the project folder, start a simple local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Project Files

- `index.html` - Page structure
- `style.css` - Board, piece, and responsive styles
- `script.js` - Game logic and interactions
