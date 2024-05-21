# Maze Solver using Python and Curses

This Python script demonstrates how to solve a maze using the breadth-first search (BFS) algorithm and visualize the process using the `curses` library. The maze is represented as a 2D grid, where `'#'` represents walls, `'O'` is the starting point, and `'X'` is the destination.

## How it works

1. **Print Maze:** The `print_maze` function prints the maze to the terminal window using colors. It optionally highlights the path in red if provided.

2. **Find Start:** The `find_start` function finds the starting position (`'O'`) in the maze.

3. **Find Path:** The `find_path` function uses BFS to find a path from the starting position to the destination (`'X'`). It uses a queue to keep track of positions to explore and a set to keep track of visited positions. The process is visualized step by step using `curses`.

4. **Find Neighbors:** The `find_neighbors` function returns a list of neighboring positions for a given position in the maze.

5. **Main Function:** The `main` function initializes the `curses` library, calls `find_path` to find the path through the maze, and waits for a key press before exiting.

