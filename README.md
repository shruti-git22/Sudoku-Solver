# TITLE : Sudoku Solver in Python 🧩 

## 🚀 Overview

- The solver uses a recursive backtracking approach, which systematically tries all possible numbers in each empty cell until it finds a valid configuration that satisfies Sudoku constraints.
- This project is a Sudoku Solver built using Python and the Backtracking Algorithm.
- It takes an unsolved 9×9 Sudoku grid and fills in all empty cells (0) while ensuring that Sudoku rules are followed.
- This project demonstrates:

Recursive problem solving

Constraint validation (rows, columns, and 3×3 subgrids)

Use of control flow and logical reasoning in Python

## Algorithm : 
The algorithm works recursively:
Find the next empty cell (value 0).

Try filling numbers 1–9 in that cell.

For each number, check if it is valid using Sudoku rules.

If valid, place the number and recursively solve the next cell.

If no valid number leads to a solution, backtrack — reset the cell to 0 and try the next possible number.

This process continues until the entire grid is filled or no valid configuration exists.

## Validation Function: is_valid_move()

Checks whether placing a number in a given cell follows Sudoku constraints:
✅ Row Check: The number must not already appear in the current row.

✅ Column Check: The number must not appear in the current column.

✅ 3×3 Subgrid Check: The number must not appear in the 3×3 box corresponding to that cell.

## Features

-Solves standard 9×9 Sudoku puzzles efficiently

-Uses recursion and backtracking

-Validates each move for row, column, and 3×3 subgrid constraints

-Clean, beginner-friendly code structure

-Can be easily extended into a GUI or web app

## What I Learned

Implementing recursion and backtracking

-How to validate Sudoku constraints programmatically

-Debugging nested loops and logical conditions

-Structuring Python functions for readability

## Here is the code snippet-

<img width="918" height="646" alt="Screenshot 2025-10-06 162256" src="https://github.com/user-attachments/assets/db13783f-8f0b-4ed7-984f-7ca03caa2ce4" />

### Example Input : 

<img width="540" height="476" alt="image" src="https://github.com/user-attachments/assets/4e618154-8743-4127-8dd3-50f1962d77ca" />

### Output :
<img width="431" height="473" alt="image" src="https://github.com/user-attachments/assets/7245b850-ac5e-4875-8594-f987e8cb1cf3" />

## Technical Details :
Code-
[Jupyter Notebook](https://github.com/shruti-git22/Sudoku-Solver/blob/main/Sudoku_Solver.ipynb)
[Python Code](https://github.com/shruti-git22/Sudoku-Solver/blob/main/Sudoku.py)


