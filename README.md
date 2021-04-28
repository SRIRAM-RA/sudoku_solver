# sudoku_validator

## Languages used:- Python 3.8.5.
## Tools used: IDLE python


Well we know sudoku is a puzzle where 9x9 matrix is used.
The algorithm to solve sudoku is simple.

1.The first step is to pick an empty cell
2.The second step is to try all possible numbers (1-9)
3.The third step is to check whether the number we entered works,(i.e) the number is cross checked with the row and then the column and then the 3x3 matrix where the cell is present.
4.The fourth step is to make sure that the number is we entered is not repeated.
5.The fifth step is, if the number we entered is repeated either in a row,or a column,or the matrix where the cell is present, if the number is present then we backtrack. 

## FUNCTIONALTY

Valid():
	This function makes sures to check the number we enter is valid or not by comparing it to every element in a row and column. If the number we entered is already present then we return false

solve():
	This function is going to call all the funcationalities where we backtrack the process if the number is not valid.
