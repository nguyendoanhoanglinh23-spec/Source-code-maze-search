# **Maze Pathfinding Comparison**

**Course Project**: Introduction to Artificial Intelligence

**Institution**: Faculty of Data Science and Artificial Intelligence – NEU College of Technology (NCT), National Economics University (NEU)

**Term**: Semester 1, Academic Year 2026–2027

**Instructor**: Dr. Nguyen Trong Nghia

**Team**: Group 05

**Repository**: 



## 1. Project Overview

This project explores maze pathfinding using three uninformed and informed search algorithms: Breadth-First Search (BFS), Depth-First Search (DFS), and Greedy Best-First Search (GBFS).

The objective is to find a valid path from a starting position to one of the available exits in a 2D grid maze.

## 2. Algorithms

* **BFS (Breadth-First Search):** Explores nodes level by level and guarantees the shortest path when all movements have equal costs.
* **DFS (Depth-First Search):** Explores one path as deeply as possible before backtracking.
* **GBFS (Greedy Best-First Search):** Prioritizes nodes based on their heuristic distance to the nearest exit.

## 3. Maze Generation

Mazes are generated using the DFS Backtracking algorithm.

Each maze contains:

* `S`: Starting position
* `E`: Exit
* `.`: Walkable cell
* `#`: Wall or obstacle

## 4. Experimental Setup

The algorithms are evaluated using four maze configurations:

| Maze Size | Number of Exits | Number of Mazes |
| --------- | --------------: | --------------: |
| 21 × 21   |               2 |             100 |
| 51 × 51   |               4 |             100 |
| 101 × 101 |               6 |             100 |
| 201 × 201 |              10 |             100 |

A total of 400 mazes are used in the experiments.

## 5. Evaluation Metrics

* Average Path Length
* Average Expanded Nodes
* Average Execution Time
* Average Peak Memory Usage
* Shortest Path Rate

## 6. Requirements

* Python 3
* NumPy
* Pandas

Install the required library using:

```bash
pip install numpy
```

## 7. How to Run

1. Clone or download this repository.
2. Open `Maze_Search_Algorithms.ipynb` using Jupyter Notebook or Google Colab.
3. Run all cells in the correct order to reproduce the experiments.

## 8. Source Code

The complete implementation and experimental results are available in this repository.
