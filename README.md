# Sudoku
Basic SUDOKU game with backtracking algorithm.

SUDOKU project that includes two files:

GUI.py
solver.py

!It is preffered to use pycharm when running this code because of pygame package.

GUI.py file creates a basic graphical user interface based of the board, the timer ,etc..
GUI is made with pygame and it imports the solver.py to solve the board.

solver.py includes the functions that checks if the player has won, if the player put the right or wrong input and the 
fuction to print the board.

When user presses the enter key the code solves the remaining board with backtracking algorithm.
The algorithm tries the numbers from 0-9 to the empty blocks. If a number is valit to that block it continues to the next one.
When no number is valid code returns to the previous block and tries the numbers that come after the entered value. If no value is valid
the algorithm goes to one before it. This continues until all the numbers in all the blocks are valid.
