# Python Sudoku Solver
##### Using Donald Knuth's dancing links algorithm
I have not removed the large quantity of commenting from the code so that it may help someone else understand the algorithm better.

---

## How To Use:
From Command Line:
>An example sudoku is given in **exampleSudoku.txt**.
>This can be used with multiple arguments each giving a text file containing a sudoku
>```
>python3 solve.py exampleSudoku.txt exampleSudoku.txt exampleSudoku.txt
>```
>This will solve each file provided in turn and print them out to the console.

---

>Additionally string arguments can be provided to the solve.py function which will also work. 

From Your Code:
>The package can be used in the following way:
>```
>from dancingLinks import solve
>
>x = [[8, 1, 0, 0, 3, 0, 0, 2, 7],
>    [0, 6, 2, 0, 5, 0, 0, 9, 0],
>    [0, 7, 0, 0, 0, 0, 0, 0, 0],
>    [0, 9, 0, 6, 0, 0, 1, 0, 0],
>    [1, 0, 0, 0, 2, 0, 0, 0, 4],
>    [0, 0, 8, 0, 0, 5, 0, 7, 0],
>    [0, 0, 0, 0, 0, 0, 0, 8, 0],
>    [0, 2, 0, 0, 1, 0, 7, 5, 0],
>    [3, 8, 0, 0, 7, 0, 0, 4, 2]]
>
>print(solve.sudoku_solver(x))
>```
>The solve file needs to be imported and the sudoku_solver function needs to be called on the sudoku you wish to solve.

#### **solve.sudoku_solver(s) returns a 9x9 2D numpy array, NOT a regular python array.**
