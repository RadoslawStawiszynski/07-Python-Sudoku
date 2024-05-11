# Python Sudoku Solver

Welcome to the Python Sudoku Solver! This Python script generates and solves Sudoku puzzles using a backtracking algorithm.

## About

This script generates a random Sudoku puzzle and attempts to solve it using a backtracking algorithm. It prints the generated puzzle, attempts to solve it, and prints the solved puzzle.

## Features

- Generates random Sudoku puzzles.
- Solves generated Sudoku puzzles using a backtracking algorithm.
- Displays the generated puzzle, solving process, and the solved puzzle.

## How to Use

1. Run the Python file `sudoku_solver.py`.
2. The script will generate a random Sudoku puzzle.
3. It will print the generated puzzle and attempt to solve it.
4. The solving process will be displayed.
5. Once solved, the script will print the solved puzzle.

## Notes

- The script may take some time to generate and solve puzzles, depending on the complexity.
- You can interrupt the script at any time using `Ctrl+C` to stop the generation or solving process.
- The script handles keyboard interrupts and errors gracefully.

## Example Output

Generated Sudoku:

- 5 . . | . . . | 6 . 7
- 4 . . | 3 6 . | . . 1
- . 7 . | . . . | . . .
- --------------------`
- . . 9 | . . . | . . .
- . . . | . . 8 | 7 . .
- . . . | . . . | . . 3
- --------------------`
- 8 . . | . . . | . . .
- . . . | 5 2 3 | . . .
- . . . | . . . | . 6 .

Solving...

- 5 3 1 | 8 9 2 | 6 4 7
- 4 9 2 | 3 6 7 | 8 5 1
- 6 7 8 | 1 4 5 | 9 3 2
- --------------------`
- 7 2 9 | 6 3 1 | 4 8 5
- 1 5 3 | 4 8 9 | 7 2 6
- 2 8 6 | 7 5 4 | 1 9 3
- --------------------`
- 8 6 4 | 9 7 1 | 3 1 5
- 3 4 7 | 5 2 3 | 2 6 8
- 9 1 5 | 2 3 6 | 5 7 4

Solved!

## Disclaimer

This script is provided for educational and demonstration purposes only. Use it responsibly and avoid relying on it for critical Sudoku solving tasks.

## Have Fun Solving Sudoku!

Enjoy using the Python Sudoku Solver to generate and solve Sudoku puzzles effortlessly!
