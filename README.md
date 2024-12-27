# Sudoku-Solver-Using-Python-and-OpenCV

A Python-based Sudoku Solver implemented in a Jupyter Notebook. This project utilizes the backtracking algorithm to solve Sudoku puzzles efficiently and interactively.

## Features
- Solves standard 9x9 Sudoku puzzles.
- Uses the backtracking algorithm for accurate and efficient solutions.
- Interactive input and visualization of Sudoku puzzles in the Jupyter Notebook.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: `numpy`, `matplotlib`

### Install Required Libraries
To install the necessary libraries, use the following command:
```bash
pip install numpy matplotlib
```

Algorithm
```
The solver uses the backtracking algorithm:

Identify the first empty cell in the grid.
Try placing numbers 1-9 in the cell.
Validate each placement against Sudoku rules.
Recursively continue until the puzzle is solved or no solution exists.
```

Author  
Krunal
