# Sudoku Solver

This is a sudoku solver using a backtracking

To finish sudoku, we need to fill the empty spaces with 0-9 numbers. The same occurs on the row, column and squares (3x3)

These empty values are represented by -1, so for example:

```

[[-1,  1,  5, ...],
 [-1, -1, -1, ...],
 [ 3, 2, -1, ...]
 ...]
 
 ```
 would represent a board like this:
 
  -----------
|     1   5 | ...
|           | ...
| 3   2     | ...
 -----------
 ...
 
 
 So, this code is to solve the sudoku puzzle using Python :D

