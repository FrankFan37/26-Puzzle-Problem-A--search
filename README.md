# 26-Puzzle-Problem-A--search

## Project Description: 
Implement the A* search algorithm with graph search (no repeated states)
for solving the 26-puzzle problem as described below. Use h(n)= Sum of Manhattan distances of
the tiles from their goal positions as heuristic function.

## The 26-puzzle problem: 
The game board consists of three 3 x 3 grids stacked together as shown
in Figure 1 below. There are 26 tiles, numbered 1 to 26, and a blank position. A tile can move into
the blank position if it is adjacent to the blank position in the x, y or z directions, as shown in the
figure. We can define six virtual moves (actions) for the blank position: East (E), West (W), North
(N), South (S), Up (U) and Down (D) (see figure below.) Given an initial state, the goal is to find a
move sequence with a minimum number of moves to reach a given goal state.

## Program Usage
- Run in command-line interface/terminal:
- python3 <main.py path> <input file path> <desired output file path>
- Example: python3 main.py /Users/Desktop/Input3.txt /Users/Desktop/Ouput3.txt
