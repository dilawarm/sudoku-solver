# A general solver for Constraint Satisfaction Problems

A solver for 9x9 sudoku puzzles using backtracking search and the arc-consistency algorithm AC-3.

This code is written as an assignment for the course __TDT4136 - Introduction to Artificial Intelligence__ :school:

## How to run
```sh
git clone https://github.com/dilawarm/sudoku-solver.git
cd sudoku-solver
```
### Make your own puzzle
Add your own 9x9 sudoku puzzle [here](puzzles/). Here is the [AI Escargot](https://www.adlibris.com/no/bok/ai-escargot---the-most-difficult-sudoku-puzzle-9781847534514) puzzle:
```sh
$ cat puzzles/ai_escargot.txt
100007090
030020008
009600500
005300900
010080002
600004000
300000010
040000007
007000300
``` 
### Solve the puzzle
```sh
python3 sudoku.py
```
```sh
Filename: ai_escargot.txt
Solution for ai_escargot.txt:
1 6 2 | 8 5 7 | 4 9 3 
5 3 4 | 1 2 9 | 6 7 8 
7 8 9 | 6 4 3 | 5 2 1 
------+-------+------
4 7 5 | 3 1 2 | 9 8 6 
9 1 3 | 5 8 6 | 7 4 2 
6 2 8 | 7 9 4 | 1 3 5 
------+-------+------
3 5 6 | 4 7 8 | 2 1 9 
2 4 1 | 9 3 5 | 8 6 7 
8 9 7 | 2 6 1 | 3 5 4 
```

Enjoy! :rocket: