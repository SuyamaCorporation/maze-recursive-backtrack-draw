# Recursive Backtracking Maze Generator

Generates perfect mazes (no loops, exactly one path between any two cells) using the recursive backtracking algorithm (iterative DFS with a stack). The generation is animated cell-by-cell, showing the frontier in a highlight color as walls are removed. After generation completes, a Solve button runs BFS to find the shortest path from the top-left corner to the bottom-right corner and animates it in blue.

## Features

- Three grid sizes: 10×10, 20×20, 30×30
- Five animation speeds: Very Slow to Instant (instant mode skips animation)
- Four color themes: Dark, Forest, Ocean, Fire
- Animated generation with current-cell highlight
- BFS solver with exploration visualization followed by shortest-path trace
- Start cell (green) and end cell (red) markers
- Stop button halts any running animation
- Status bar reports generation progress and solved path length
- Accessible: ARIA live region for status, labeled sliders, descriptive canvas role
