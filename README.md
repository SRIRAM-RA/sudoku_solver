# sudoku_validator

## Languages used:- Python 3.8.5.
## Tools used: IDLE python


Well we know sudoku is a puzzle where 9x9 matrix is used.
The algorithm to solve sudoku is simple.

1. The first step is to pick an empty cell.
2. The second step is to try all possible numbers (1-9).
3. The third step is to check whether the number we entered works,(i.e) the number is cross checked with the row and then the column and then the 3x3 matrix where the cell is present. 
4. The fourth step is to make sure that the number is we entered is not repeated.
5. The fifth step is, if the number we entered is repeated either in a row,or a column,or the matrix where the cell is present, if the number is present then we backtrack. 


## Files Info
The repository consists of two files
1. GUI.py
2. solver.py

## Required modules
1. "pygame" this module is used to make the sudoku gui.  

## FUNCTIONALTY

1. Valid():
	This function makes sures to check the number we enter is valid or not by comparing it to every element in a row and column. If the number we entered is already present then we return false.

2. solve():
	This function is going to call all the funcationalities where we backtrack the process if the number is not valid.
	
3. print_board():
	This function simply prints the sukodu format and checks whether this is valid or not.
	
## Results without gui 

![sudokuboard](https://user-images.githubusercontent.com/55801381/116355638-bf2c5580-a817-11eb-9b01-9b768acdc2e9.PNG)

The above snap denotes the format of the sudoku board.

![finished sudoku solu](https://user-images.githubusercontent.com/55801381/116355773-f569d500-a817-11eb-8e7b-ca045865054d.PNG)

This above snap shows the finished model of the sudoku board with random values that matches the constraints of the sudoku game.

