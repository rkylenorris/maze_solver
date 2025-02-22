# Maze Generator and Solver

**Objective**:
Build a Python program that first generates a random maze and then finds a path from the maze’s start to finish.

----

## **Challenge Breakdown**:

1. **Maze Generation**:

- **Algorithm Choice**:
Use an algorithm such as Depth-First Search (DFS) (recursive backtracking) or Prim's algorithm to carve out a maze on a 2D grid.
- **Representation**:
Represent the maze as a grid (e.g., a list of lists) where each cell can be a wall or a path.
- **Customizability**:
Let the user define the maze dimensions (e.g., width and height).

2. **Maze Solving**:

- **Pathfinding Algorithm**:
Implement a solver using either Breadth-First Search (BFS) to ensure you find the shortest path or even try A* for a heuristic approach.
- **Start/End Points**:
By default, set the start at the top-left cell and the end at the bottom-right cell, but consider letting the user choose these points.
- **Output**:
Display the maze with the solution path highlighted. You could use ASCII art for a terminal display or even a library like matplotlib for a graphical visualization.

3. **Enhancements (Optional for Extra Challenge)**:

- **Interactive Visualization**:
Use a GUI library (like pygame) or an animation with matplotlib to visualize the maze generation and solving process in real time.
- **Multiple Algorithms**:
Allow the user to choose different algorithms for both generation and solving to compare their performances.
- **Performance Metrics**:
Track and display the time or steps taken to generate and solve the maze.
- **Error Handling**:
Include checks for edge cases, such as very small maze sizes or non-solvable configurations (if you decide to implement variations).
---
## What You’ll Learn:

- **Algorithm Design**:
Gain experience with recursive algorithms, search strategies, and heuristic methods.
- **Data Structures**:
Work with grids, stacks (for DFS), queues (for BFS), and possibly priority queues (for A*).
- **Visualization**:
Learn how to represent data visually either in the terminal or using external libraries.
- **User Interaction**:
Practice capturing user input to adjust parameters dynamically.
