## Sudoku Puzzles
Here is a small collection of sudoku puzzles.  Each set contains a puzzle file *(\*P.txt)* and a solution file *(\*S.txt)*.  Puzzles and solutions are stored in a simple text format.  If a square has a value, a number appears.  If a square is unsolved, it is represented by a period ('.'). Data is stored in row-major order (square A1 A2 A3... A9 B1 B2 B3...I8).

Here is an example puzzle string:
```
.4....179..2..8.54..6..5..8.8..7.91..5..9..3..19.6..4.3..4..7..57.1..2..928....6.
```

which represents the Sudoku puzzle

```
     1   2   3    4   5   6    7   8   9
  =========================================
A || . | 4 | . || . | . | . || 1 | 7 | 9 ||
B || . | . | 2 || . | . | 8 || . | 5 | 4 ||
C || . | . | 6 || . | . | 5 || . | . | 8 ||
  || - - - - - || - - - - - || - - - - - ||
D || . | 8 | . || . | 7 | . || 9 | 1 | . ||
E || . | 5 | . || . | 9 | . || . | 3 | . ||
F || . | 1 | 9 || . | 6 | . || . | 4 | . ||
  || --------- || --------- || --------- ||
G || 3 | . | . || 4 | . | . || 7 | . | . ||
H || 5 | 7 | . || 1 | . | . || 2 | . | . ||
I || 9 | 2 | 8 || . | . | . || . | 6 | . ||
  =========================================
```
