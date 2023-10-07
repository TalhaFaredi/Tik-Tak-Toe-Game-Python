# Tic-Tac-Toe Game

This is a simple command-line implementation of the classic game of Tic-Tac-Toe in Python. Players can take turns to make their moves, and the game checks for a win or a draw.

## How to Play

1. Clone or download this repository to your local machine.

2. Open your terminal or command prompt and navigate to the directory where the code is located.

3. Run the following command to start the game:

   ```python
   python tictactoe.py
# Tik-Tak-Toe-Game-Python
Tik Tak toe Game Made in Python

The game will display the Tic-Tac-Toe board, and players will take turns entering their moves.

X's turn: Enter a number (0-8) to place an 'X' on the board.
O's turn: Enter a number (0-8) to place an 'O' on the board.
The game will continue until one player wins or the game ends in a draw.

Code Explanation
The game is implemented in a Python script called tictactoe.py.

It uses a simple board represented as lists for xState and zstate, where 'X' and 'O' moves are marked as 1, and empty cells are marked as 0.

The printboard function displays the current state of the board.

The Checkwins function checks for a win by examining all possible winning combinations.

The game alternates between X and O turns using the turn variable.

When the game ends, the result is displayed, and the program terminates.
