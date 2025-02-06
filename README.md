# KenKen Puzzle Solver
This project is a Python implementation of a KenKen puzzle solver. KenKen is a logic puzzle that combines elements of Sudoku and arithmetic operations. The solver supports two approaches:

Backtracking Algorithm: A recursive approach to fill the grid while ensuring row, column, and cage constraints are satisfied.

Constraint Satisfaction Problem (CSP): A domain-based approach to solve the puzzle by reducing the search space using constraints.

## Features:
* **Puzzle Generation:** Generates random KenKen puzzles of a given size.

* **Cage Generation:** Randomly creates cages with arithmetic operations (+, -, *, /) and calculates target values.

* **Solver:** Implements both backtracking and CSP-based solvers to find valid solutions.
