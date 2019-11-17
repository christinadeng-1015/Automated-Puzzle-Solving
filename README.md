# Automated-Puzzle-Solving

Puzzle solving is a typically human activity that, in recent decades, is being explored in the context of computers. There are two benets to this: rst, we can load some puzzle-solving tasks to computers, and second, we may understand human puzzle-solving better by studying how to implement it on a computer.
This assignment investigates a class of puzzles that have the following features in common:
* full information: all information about the puzzle conguration at any given point is visible to the solver; there are no hidden or random aspects

* well-dened extensions: a denition of legal extensions from a given puzzle conguration to new congurations is given

* well-dened solution: a denition of what it means for the puzzled to be in a solved state is given

These features are common to a very large class of puzzles: crosswords, sudoku, peg solitaire, verbal arithmetic, and so on. This assignment generalizes the required features into an abstract superclass Puzzle, and solving functions are written in terms of this abstract class. Once this is done, particular concrete puzzles can be modelled as subclasses of Puzzle, and solved using
the solving functions. Although there may be faster puzzle-specic solvers for a particular puzzle by knowing specic features of that puzzle, the general solvers are designed to work for all puzzles of this sort.

# Puzzle
 
* sudoku

* peg solitaire

* word ladder

* mn puzzle

# Searching 

* Depth first search (DFS)

* Breadth first search (BFS)

## Copyright and License
Automated Puzzle Solving is written by Christina Deng and Junkang Zhang.

(Starter Code is provided by University of Toronto Computer Science Department.)