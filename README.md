# Tick Cross Game (Tic-Tac-Toe) with Colorful Console Interface

This is a simple implementation of the classic Tic-Tac-Toe game in C++. The game features a user-friendly console interface with colorful text to distinguish between Player X and Player O.

## Features:
- **Two-Player Mode:** The game allows two players to take turns and mark their moves on a 3x3 grid.
- **Colorful Interface:** The console text is color-coded for an enhanced user experience:
  - Player X is highlighted in red.
  - Player O is highlighted in yellow.
- **Real-Time Updates:** The game board is updated in real-time after each move, and the screen is cleared to show the latest state of the game.
- **Win Detection:** The game detects when a player wins or when the game ends in a draw.
- **Replay Option:** After the game ends, the program prompts the user to restart or exit.

## How to Play:
1. Run the program in a Windows environment.
2. Players take turns to enter a number between 1 and 9 to place their mark (X or O) on the board.
3. The game will automatically check for a winner after each move.
4. If all cells are filled and no player has won, the game will declare a draw.

## Code Breakdown:
- **`display_board()`**: Clears the screen and displays the current state of the game board with color-coded player indicators.
- **`player_turn()`**: Handles player input and updates the board with the appropriate mark (X or O) based on the player's turn.
- **`Game_Over()`**: Checks the board for any winning conditions or a draw.
- **`main()`**: The main loop that runs the game, calling the necessary functions until the game is over.

## Requirements:
- **Operating System:** Windows (due to the use of `windows.h` for console color manipulation)
- **Compiler:** A C++ compiler that supports the Windows API (e.g., MinGW, Visual Studio)

## Usage:
Clone the repository and compile the code using your preferred C++ compiler. Run the executable to start playing.

---
