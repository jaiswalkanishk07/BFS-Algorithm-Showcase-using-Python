# Breadth-First Search (BFS) Grid Traversal with Custom Movement Rules

## Overview
This repository contains a Python implementation of the **Breadth-First Search (BFS)** algorithm to find the minimum number of moves required to reach a destination in a 2D grid, given a custom movement rule.

The program:
- Accepts grid dimensions
- Accepts a binary grid (0 = free cell, 1 = blocked cell)
- Accepts source and destination coordinates
- Accepts a custom movement rule in the form `(dx, dy)`
- Uses BFS to compute the shortest number of moves

---

## Features
- **Customizable Movement Rule** – Move in specified directions (forward, backward, left, right based on rule)
- **Shortest Path Guarantee** – BFS ensures the shortest number of moves in an unweighted grid
- **Handles Obstacles** – Cells with `1` are treated as blocked
- **Clear Error Handling** – Returns `-1` if the destination is unreachable

---

## File Structure
 bfs-grid-custom-move
├── bfs_custom_move.py # Main BFS implementation
└── README.md # Documentation

---

## How to Run
```bash
python bfs_custom_move.py

