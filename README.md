# Connect Four Game

This is a simple **Connect Four** game implemented using JavaScript, HTML, and CSS. Players take turns dropping pieces into a grid, and the first to connect four pieces in a row, column, or diagonal wins!

## Features

- **Two-Player Mode**: Red and Yellow players alternate turns.
- **Interactive Grid**: Click to drop pieces into the columns.
- **Win Detection**: Checks for horizontal, vertical, and diagonal victories.
- **Local Storage Support**: Saves game state between sessions.
- **Simple UI**: Built with JavaScript, no external libraries required.

## Technologies Used

- **HTML** – Structure of the game board
- **CSS** – Styling for the game UI
- **JavaScript** – Game logic and local storage management

## How to Play

1. Open the `index.html` file in a browser.
2. Click on a column to drop a piece.
3. The game alternates between **Red (R)** and **Yellow (Y)** players.
4. The first player to connect **four pieces** wins.
5. The winner is displayed on the screen.
6. The game state is saved in **Local Storage**.

## File Structure
/connect-four │── index.html # Main HTML file │── styles.css # Styling file │── script.js # JavaScript logic │── assets/ # Images & icons │── README.md # Project documentation

## Game Logic

1. **Grid Initialization**  
   - The board is a **6x7 grid** initialized with empty spaces.
   - Event listeners are added to each cell.

2. **Placing a Piece**  
   - The piece falls to the lowest available row in the selected column.
   - The color of the piece changes based on the **current player**.

3. **Win Conditions**  
   - The game checks for a winning sequence in:
     - **Horizontal** (left to right)
     - **Vertical** (top to bottom)
     - **Diagonal** (both directions)

4. **Game Over**  
   - The game announces the **winner** and stops further moves.

5. **Local Storage**  
   - The game state is stored using `localStorage`.
   - The saved game is loaded when the page is refreshed.

## Future Enhancements
- **AI Mode** for single-player gameplay.
- **Leaderboard** to track scores.

## Contributing

If you'd like to improve the game, feel free to fork the repository and submit a pull request.

---
Enjoy playing Connect Four! 🎮🔥
