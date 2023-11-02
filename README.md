# Chess Game

Welcome to our Chess Game project! This is a simple yet engaging implementation of the classic game of chess, designed to run in a web browser.

## Table of Contents
1. [Features](#features)
2. [How to Play](#how-to-play)
3. [Technologies Used](#technologies-used)
4. [Contributing](#contributing)

## Features

- **Interactive Chessboard**: A fully functional chessboard (`Board.js`) allowing players to move pieces according to chess rules.
- **Game Logic**: The `Game.js` file encapsulates the core game logic, managing player turns, moves, and game status.
- **Chess Pieces**: Each chess piece (Pawn, Rook, Knight, Bishop, Queen, King) is implemented in separate files under the `pieces` directory. These files (`Pawn.js`, `Rook.js`, `Knight.js`, `Bishop.js`, `Queen.js`, `King.js`) define the movement and behavior of each piece.
- **Piece Inheritance**: All pieces inherit from a base `Piece.js` class, ensuring a clean and maintainable code structure.
- **User Interface**: The game features a simple yet intuitive user interface (`chess.html`, `chess.css`), making it easy for players to interact with the game.

## How to Play

1. **Setup**: Clone the repository and open `chess.html` in a web browser.
2. **Playing the Game**: Click on a chess piece to see its available moves. Click on a highlighted square to move the selected piece.
3. **Winning the Game**: The game follows standard chess rules. Checkmate the opponent's king to win!

## Technologies Used

- JavaScript: Core game logic and chess piece behavior.
- HTML/CSS: User interface and styling.

## Contributing

Feel free to fork this repository and submit pull requests. We welcome contributions to improve the game, fix bugs, or enhance the user interface.
