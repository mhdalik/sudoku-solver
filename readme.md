# Sudoku Solver
Sudoku solver using html, CSS and JavaScript

## Algorithm to solve a sudoku
Write down the steps to solve before starting the coding

1. input the board size (e.g: 3x3, 6x6, 9x9,...), initially just start with 9x9 board
1. define an array to hold the confirmed number in each cells [array main]
1. define an array to hold the possible numbers in each cells [array possibilities]
1. Input the initial values of sudoku to be solved.
1. Run **fillPossibilities()** once  
1. Define functions of each ways to find missing numbers:
    - like function named find missing by **checkEachRows()**:   
    traverse on each rows and check missing values, if a row missing only 1 value then fill that value by finding missing value from series
    e.g: for 9x9 sudoku, row =[1,null,3,4,5,6,7,8,9]
    the missing value is 2, so row =[1,2,3,4,5,6,7,8,9]
    <!-- - function **checkEachCols()**:   -->
    - function **checkSingleCandidateInEachCells()**  
    - function **checkUniqueCandidateInEachCubes()**  
    - function **checkUniqueCandidateInEachRows()**  
    - function **checkUniqueCandidateInEachCols()**   
1. loop on each method for finding missing numbers until cannot get a single number in every iteration
1. loop on each method for finding
1. 


## Other Functions

- setValueToCell(value,rowIndx,colIndx):   
 to set value of main array

- displaySoduku():   
 to display (update dom) changes/latest sudoku data from main array