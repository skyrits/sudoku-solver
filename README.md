# sudoku_solver
## A JavaScript Sudoku Solver

This script demonstrates a backtracking algorithm application, implemented in JavaScript.

## Pseudocode:
```
Define a 2D 9x9 Array and fill it with the problem values (use 0 at empty cells).
Find row, col of an unassigned cell (cell[row,col] with 0)
If there is none, return true (problem solved)
For digits from 1 to 9
	If there is no conflict for digit at cell[row,col]
		Assign digit to cell[row,col] and recursively try fill in rest of board
		If recursion successful, return true
		If not successful, remove digit and try another
If all digits have been tried and nothing worked, return false to trigger back tracking
```
