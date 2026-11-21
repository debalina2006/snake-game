# Tic-Tac-Toe
# Tic Tac Toe Game

## Overview

This is a simple **Tic Tac Toe** game built using **HTML, CSS, and JavaScript**.
Two players can play the game in the browser by taking turns marking **X** and **O** on a 3×3 grid.

---

## Features

* Interactive 3×3 game board
* Two-player gameplay
* Automatic win detection
* Draw detection
* Board reset after game ends
* Responsive and clean UI design

---

## Technologies Used

* **HTML** – Structure of the game
* **CSS** – Styling and layout
* **JavaScript** – Game logic and interactivity

---

## Project Structure

```plaintext
tic-tac-toe/
│
├── index.html
└── README.md
```

---

## How to Run the Project

1. Download or copy the project files.
2. Save the code in a file named `index.html`.
3. Open the file in any modern web browser.

---

## Game Rules

1. Player **X** starts first.
2. Players take turns placing their marks.
3. The first player to get:

   * 3 marks in a row,
   * 3 marks in a column, or
   * 3 marks diagonally
     wins the game.
4. If all cells are filled and no player wins, the game ends in a draw.

---

## Main Functions

### `handleClick(event)`

Handles player moves when a cell is clicked.

### `checkWin(player)`

Checks if the current player has won the game.

### `isDraw()`

Checks whether the game is a draw.

### `resetBoard()`

Clears the board and starts a new game.

---

## Future Improvements

* Add single-player mode with AI
* Add score tracking
* Add restart button
* Add sound effects and animations
* Make the design mobile-friendly

---

## Author

Created as a simple web-based Tic Tac Toe project using HTML, CSS, and JavaScript.
