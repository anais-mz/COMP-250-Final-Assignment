# COMP-250-Final-Assignment

This was the final assignment for my COMP 250 class. For this, we were required to create a Sudoku solver. Not only is the code 
able to solve regular Sudoku puzzles, but it also has the capacity to solve Chess-Sudokus. The rules of Chess-Sudoku are as follows:

1. Knight Rule: a digit must not appear a chess knight's move away from itself. Knights in chess move forming
an L shape: either two squares vertically and one horizontally, or two squares horizontally and one vertically.

2. King Rule: a digit must not be a King's move away from itself. Which to the classical rules of Sudoku only adds
the fact that a digit cannot be a single diagonal move away from itself.

3. Queen Rule: every 9 in the grid acts like a chess Queen and must not be in the same row/column/3x3 box or diagonal 
of any other 9. 

This solver can also solve grids ranging from 3x3, 4x4, and 5x5. Important to note that for the Queen Rule, if the grid
is 4x4 then the rule applies only to the 16s. 
