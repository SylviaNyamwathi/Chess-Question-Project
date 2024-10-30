# Chess Question Project

## Project Overview
This project is a Python-based console application designed to analyze a given chessboard state. The program prompts the user to input the positions of a white chess piece and up to 16 black pieces. It then identifies which black pieces the white piece can capture based on their positions and the rules of movement for each piece.

## Features
- **Piece Selection:** The program allows the user to choose a white chess piece from a predefined list of two pieces (e.g., knight and rook).
- **Black Pieces Input:** Users can add up to 16 black pieces in a predefined format.
- **Move Validation:** The program checks if the black pieces can be taken by the white piece based on the chess rules.
- **Input Confirmation and Error Handling:** Each successful addition or error is communicated clearly to the user.
- **Flexible Input:** The program gracefully handles user input and termination.

## User Instructions
1. Start by entering the white piece and its position in the format: `piece coordinates` (e.g., `rook d4`).
2. Input black pieces one by one in the same format: `piece coordinates` (e.g., `pawn e5`).
3. When finished, enter `done` to stop adding black pieces.
4. The program will display which black pieces can be captured by the white piece based on its moves.

## Assumptions Made
- Users will always provide valid piece names and coordinates within the chessboard range.
- The white piece can only capture pieces based on standard chess movement rules.
- Coordinates are entered in the format of a letter (a-h) followed by a number (1-8).
