# Conways_Game_of_Life_Python
An implementation of "Conway's Game of Life"  (Cellular Automaton) in Python. This is just a simple coding example in Python.

For background see this Wikipedia article:

https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

Yes I know doing this in Python will be slow. This is _not_ optimized for speed or showing special coding tricks.   
Understand my design intent with this demonstration: I'm not demonstrating "leetcode" style hacks like Lambda functions, etc. because they make the code very difficult to follow/understand. To me, the purpose of Python is to make easy-to-read scripts for tools and automating tasks. If you really wanted to go faster, I'd make this in C++ with CUDA (See my other coding example for that).

# Background:
From [the wikipedia article](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life):
```
Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

    Any live cell with fewer than two live neighbours dies, as if by underpopulation.
    Any live cell with two or three live neighbours lives on to the next generation.
    Any live cell with more than three live neighbours dies, as if by overpopulation.
    Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.
```
