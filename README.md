# Sudoku Solver

## Description
This project is a Sudoku solver implemented in Python using the Pygame library for the graphical user interface. The solver uses a backtracking algorithm to find a solution to a given Sudoku puzzle. The program provides a visual representation of the Sudoku board and allows the user to view the solved board.

## Features
- Reads a Sudoku puzzle from a text file.
- Displays the initial unsolved Sudoku board using Pygame.
- Solves the Sudoku puzzle using a backtracking algorithm.
- Displays the solved Sudoku board using Pygame.
- Highlights the pre-filled numbers in blue on the Sudoku board.
- Draws a grid on the Sudoku board for better visualization.

## Files
- `Grid.py`: Contains the code to read the input Sudoku board from a text file and store it in a grid.
- `SudokuBoard.py`: Implements the graphical user interface using Pygame. Displays the Sudoku board and the solved numbers.
- `Sudoku_Solver.py`: Implements the Sudoku solving algorithm using a backtracking approach. Provides functions to find blank spaces, check if a number is valid, and solve the puzzle.
- `input_sudoku board.txt`: Text file containing the input Sudoku puzzle.
- `assets/Kalam-Regular.ttf`: Font file used for displaying numbers on the Sudoku board.
- `test.py`: A test script to read the input Sudoku board from a text file and store it in a grid.

## Dependencies
- Python 3.x
- Pygame library

## Usage
1. Clone the repository or download the project files.
2. Install the Pygame library if it's not already installed: `pip install pygame`.
3. Run the `SudokuBoard.py` file using Python: `python SudokuBoard.py`.
4. The Sudoku board will be displayed, showing the initial unsolved puzzle.
5. The program will solve the Sudoku puzzle using the backtracking algorithm and display the solved board.
6. The pre-filled numbers in the Sudoku board will be highlighted in blue.
7. Close the Pygame window to exit the program.

Feel free to modify the `input_sudoku board.txt` file to solve different Sudoku puzzles. Each number in the text file should be separated by a space, and each row should be separated by a new line.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.
