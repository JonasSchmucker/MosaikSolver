# Mosaik Solver

a solver for the popular puzzle game [Mosaik](https://de.puzzle-minesweeper.com/mosaic-5x5-easy/).
This solver utilizes the z3 SAT-solver

## Usage

```bash
./main.py levels/prod_15x15.csv
```

Output:

```
Detected level size: 15x15
  4 3     2 1     1 3 3 4 4 3 
4 5 3       4 4 3 3   4 4   3 
2 3 3 3     5   4     3 3     
      4     5 4     2 2       
    5   5 5   4             2 
  8 6 4       4     3 4 4 4   
4 5 5               4   4   1 
3   5 7 8 7 4 3   4   4   1   
    5     7 5 5 4     1     1 
        6 6     5   2   2 3 3 
4         5     6 3 1   2 5   
4   6 4     5 6     1 1       
3   4       3 3   5 3 3 2   2 
  4   5     4     5 4   3   3 
1 1 1     4 3 1 3     3     3 

X X X O X O O O O O O X X O X 
O X O O O O X O O X O X O X X 
X O O O O X X X X O X O O O O 
O O X X X X O O O X O O X O O 
X X X O O X O O X O O O O O X 
X X O O O X X X X O O O X X O 
X X X X X X O O O X X X X O O 
O O O X X X X O O X O O O O O 
X O O X X O X O X O O X O O O 
X X X X X O X X O X O O O O X 
O X O X O X X X X O O O O X X 
O X O O X O O X X O O O X O X 
X X X X O X O O X X O O O O O 
O O O O X X O O O X X O X O X 
X O O X X X O X O X O O X X X 
```
