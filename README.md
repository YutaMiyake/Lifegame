# Life game

## What is life game?
http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

### Conway's Game of Life or Life:
a cellular automation devised by the British
mathematician John Horton Conway in 1970

### RULES of the life:
For the life, the universe is an infinite 2D orthogonal grid of square cells.
Each of which has either two states, alive or dead. Every cell interacts with
eight neighbours which are the cells that are horizontally, vertically, or
diagonally adjacent. At each step in time,
the following transitions occur:

1. Any live cell with fewer than two live neighbours dies, as if caused by under population.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overcrowding.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

The initial pattern constitutes the seed of the system. The first generation is
created by applying the above rules simultaneously to every cell in the
seed, and births and deaths occur at the same time. Each following generation is
a result of applying the function or rules to the preceding one. The rules
continue to be applied repeatedly to create further generations.

## Requirements
* python 3.xx
* [pygame](http://www.pygame.org/download.shtml)

## Usage
```bash
$ python3 life.py
```

## Screenshots
![Alt testcase ](/screenshots/screenshot1.png?raw=true "testcase")

## Reference
http://aidiary.hatenablog.com/entry/20080914/1281748797

## Licence
* MIT License

## Author
* Yuta Miyake