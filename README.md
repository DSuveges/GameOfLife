# John Conway's game of life implemented on python

Just a little bit of playing around with the famous evolving model system designed by [John Conway](https://en.wikipedia.org/wiki/John_Horton_Conway) called [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life). Although the rules of the system is extremely simple, an astounishing complexity of "organisms" can be created. Surprisingly, since the initial publication of the system in the 1970s, mathematicias are still actively researching the emerging strucures and by this day and over 8000 patterns have been identified from a dozens of established classes.

### The rules:

* The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead.
* Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent.
* Any live cell with fewer than two live neighbours dies, as if caused by under-population.
* Any live cell with two or three live neighbours lives on to the next generation.
* Any live cell with more than three live neighbours dies, as if by over-population.
* Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

### Contents:

In this notebook, a game of life engine is implemented in python, with 3 possible mechanism of pattern genergations:
* Paterns can be randomly generated ("soup").
* An established pattern can be downloaded from the [cetral pattern library](http://www.conwaylife.com/wiki/Category:Patterns).
* A bitmap of a pattern can be read pixel by pixel to reconstruct the pattern.

__An example input for the latter solution:__

![GOL input bimap](https://raw.githubusercontent.com/DSuveges/GameOfLife/master/Breeder_wiki.png)

The ipython notebook contains steps to generate nice animation as well.