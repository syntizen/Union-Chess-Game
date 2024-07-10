# Expanded Aggressive Chess Game (24x12)(24x16)

Welcome to the Expanded Aggressive Chess Game! This game is a custom implementation of chess with an enlarged board of 24x12 and three sets of pieces for each player. The game automatically makes moves based on a simplified AI.

## Features

- **Chess Board**: A unique chess variant with an expanded board and three sets of pieces for each player.
- **Automatic Moves**: Moves are automatically generated and made by the AI for both players.
- **Game Status**: Displays the current turn and the game status (ongoing, checkmate, or stalemate).
- **Pause and Resume**: You can pause and resume the game at any time.
- **Game Over Dialog**: A dialog appears when the game is over, indicating the winner and providing an option to play again.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/syntizen/expanded-aggressive-chess.git
   cd expanded-aggressive-chess
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm start
   ```

4. **Open your browser and navigate to:**

   ```
   http://localhost:3000
   ```

## Usage

### Playing the Game

- The game starts automatically and makes moves for both players.
- You can pause and resume the game using the "Pause" and "Resume" buttons.
- The current turn and game status are displayed above the board.
- When the game is over, a dialog will appear indicating the winner. You can start a new game by clicking "Play Again".

## Code Structure

### `ChessGame` Component

- **State Management**: Uses React hooks (`useState`, `useEffect`) to manage the game state.
- **Board Rendering**: Renders the 24x12 board and pieces using Unicode characters.
- **Move Logic**: Implements basic AI to generate and make moves for both players.
- **Game Over Handling**: Checks for checkmate and stalemate conditions and displays the game over dialog.

### Piece Movements

- **Piece Values**: Defined in `pieceValues` for evaluation.
- **Piece Moves**: Functions to get possible moves for each piece type.
- **Move Validation**: Ensures moves are within the board limits and follow chess rules.

## Contributing

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/my-new-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/my-new-feature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions or feedback, please contact me at [syntizen@gmail.com].

Happy playing!
