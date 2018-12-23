# gameoflife

Your task is to write a program to calculate the next
generation of Conway's game of life, given any starting
position.

You start with a two dimensional grid of cells, where
each cell is either alive or dead. The grid is finite,
and no life can exist off the edges. When calculating
the next generation of the grid, follow these four rules:

1. Any live cell with fewer than two live neighbours
   dies, as if caused by underpopulation.
2. Any live cell with more than three live neighbours
   dies, as if by overcrowding.
3. Any live cell with two or three live neighbours
   lives on to the next generation.
4. Any dead cell with exactly three live neighbours
   becomes a live cell.

问题描述：
细胞自动机，由一堆格子构成的封闭空间，尺寸为N的空间就有 N×N 个格子。每一个格子旁边都由邻居格子存在。 每个格子的生死遵循下面的原则：
1：如果一个活细胞周围有两个或者三个活细胞，则这个细胞为生。
2：如果一个活细胞周围少于两个活细胞，则这个细胞死亡。
3：如果一个活细胞周围有超过三个活细胞，则这个细胞死亡。
4：如果一个死细胞周围有三个活细胞，则这个细胞为生。

Examples: 1 indicates live cell, 0 indicates dead cell

Example input: (3*3 grid)
1 0 1
0 1 0
1 0 1

Example output:
0 1 0
1 0 1
0 1 0

# Tools
java
junit4
vim
git & github
breaktime

# Way of working
Pair programming
TDD
Step by Step
Take a break per 45 mins

# Principle
Limit test red phase.
Only when the code is in a safe state do we agree to do Code optimization and improvement.


# TODO



