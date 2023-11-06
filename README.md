
# Sudoku Solver

A Sudoku solver project using HTML, CSS, and JavaScript, implementing a popular Sudoku solving algorithm.

## Table of Contents

- [About](#about)
- [Features](#features)
- [How to Use](#how-to-use)
- [Algorithm](#algorithm)

## About

This project is a Sudoku solver web application built using HTML, CSS, and JavaScript. It provides a simple and intuitive interface for solving Sudoku puzzles and also includes a solver algorithm to automatically solve Sudoku puzzles.



## Features

- Interactive Sudoku grid with easy-to-use interface.
- Solves Sudoku puzzles of varying difficulty.
- Clears the entire grid or individual cells for user input.
- Validates the user's input and provides feedback.
- Provides an option to automatically solve the puzzle using a popular Sudoku solving algorithm.

## How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/sudoku-solver.git
   ```

2. Open the `index.html` file in your web browser to use the Sudoku solver.

3. To input numbers, simply click on the cell you want to edit, type the number, and press Enter.

4. To clear a cell, click on it and press the "Delete" or "Backspace" key.

5. To solve a puzzle, click the "Solve" button, and the algorithm will solve it for you.

## Algorithm

This Sudoku solver uses a popular backtracking algorithm to find the solution to Sudoku puzzles. It works by iteratively trying numbers in empty cells and backtracking when a conflict is detected, eventually arriving at the correct solution.

The JavaScript code for the solver algorithm can be found in the `solver.js` file in this repository.

---
