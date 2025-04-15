# ⭐ A* Pathfinding Visualization with Pygame

This project is a visual simulation of the A* (A-star) pathfinding algorithm built using Python's `pygame` library. It allows users to interactively create a grid, set a start and end point, place obstacles, and watch the algorithm find the shortest path in real-time.

## 🎮 How It Works

The grid is made up of cells, and each cell can be assigned a different role:

- 🟧 **Orange** – Start Node  
- 🟦 **Cyan** – Destination Node  
- ⬛ **Black** – Blockages / Obstacles  
- 🟩 **Green** – Currently Visiting Node  
- 🟥 **Red** – Already Visited Node  
- 🟪 **Purple** – Final Path Highlight

The A* algorithm calculates the shortest path from the start to the destination, considering both distance and estimated cost.

## 🧠 Algorithm

- Uses the **A\*** search algorithm with `f(n) = g(n) + h(n)`
- `g(n)` = distance from start to current node
- `h(n)` = heuristic (Manhattan distance)
- Efficient and optimal for most grid-based pathfinding problems

## 🕹️ Controls

- **Left Click**: Draw Start, End, and Blockages
- **Right Click**: Remove elements
- **Spacebar**: Start the A* algorithm simulation
- **C**: Clear the grid and reset

## 📦 Requirements

- Python 3.x
- `pygame` library

Install dependencies using pip:

```bash
pip install pygame
