Maze Path Finder Visualization
=============================

A terminal-based maze pathfinding visualizer built with Python and the curses library. This project demonstrates how to use breadth-first search (BFS) to find the shortest path in a maze, with real-time visualization in the terminal.

---

## Key Features

- **Maze Visualization:** Displays the maze and the pathfinding process in real time using colored output in the terminal.
- **Breadth-First Search (BFS):** Implements BFS to guarantee the shortest path from the start ('O') to the end ('X').
- **Step-by-Step Animation:** Shows the search progress and the discovered path as it is being found.
- **Customizable Maze:** The maze structure can be easily modified in the code.
- **Color Feedback:** Uses different colors to distinguish between walls, open paths, and the found path.

---

## Requirements

- Python 3.x
- curses (standard on Unix/Linux/macOS; for Windows, install with `pip install windows-curses`)

---

## How to Run

1. Make sure you have Python 3 installed.
2. Run the script:
   ```
   python path_finder.py
   ```
3. Watch as the algorithm finds the shortest path from 'O' (start) to 'X' (end) in the maze.
4. Press any key to exit after the visualization completes.

---

## Example Visualization

```
# O # # # # # # #
#   . . . . . . #
#   # # . # #   #
#   # . . . #   #
#   # . # . #   #
#   # . # . #   #
#   # . # # #   #
#   . . . . .   #
# # # # # # # X #
```
(Where '.' or 'X' in red shows the discovered path)

---

## Key Learnings

- **Breadth-First Search:** Implementing BFS for shortest path finding in a grid/maze.
- **Curses Library:** Creating real-time, colored terminal visualizations.
- **Queues and Data Structures:** Using Python's `queue.Queue` for BFS and sets for visited nodes.
- **Animation and Timing:** Using `time.sleep()` to animate the search process.
- **Function Decomposition:** Organizing code into clear, reusable functions for maintainability.
- **Debugging Visualization:** Visual feedback helps in understanding and debugging pathfinding algorithms.

---
