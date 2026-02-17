AI Pathfinder – Visual Search Algorithms

A Python-based visualization tool that demonstrates uninformed search algorithms using Pygame. This project allows users to see how different algorithms explore a grid step-by-step to find a path from a start point to a target.

---

 Features

* 6 search algorithms with real-time visualization:

  * BFS (Breadth-First Search)
  * DFS (Depth-First Search)
  * UCS (Uniform-Cost Search)
  * DLS (Depth-Limited Search)
  * IDDFS (Iterative Deepening DFS)
  * Bidirectional Search
* Interactive grid to place:

  * Start node
  * Target node
  * Obstacles (walls)
* Live statistics display:

  * Nodes explored
  * Path length
  * Frontier size
  * Execution time
* Adjustable visualization speed
* Dynamic obstacles appearing during search
* Pause / Resume, Reset, and Clear controls

---

Requirements

* Python 3.7 or higher
* Pygame 2.0 or higher

---

Installation

Step 1: Clone the Repository

```
git clone https://github.com/MaryamZahid-gh/AI-PathFinder-Project
```

Step 2: Open Project Folder

```
cd ai-pathfinder
```

Step 3: Install Dependencies

```
pip install -r requirements.txt
```

Or install manually:

```
pip install pygame
```

---

Running the Application

Run the following command:

```
python gui_main.py
```

This will open the visualization window.

---

 Controls

| Action                               | Control     |
| ------------------------------------ | ----------- |
| Select algorithm (BFS–Bidirectional) | Keys 1–6    |
| Start / Pause visualization          | SPACE       |
| Reset search                         | R           |
| Clear grid                           | C           |
| Adjust speed                         | + / -       |
| Exit application                     | ESC         |
| Place start, target, walls           | Mouse Click |

---

Algorithms Overview

| Algorithm     | Description                        | Optimal | Complete |
| ------------- | ---------------------------------- | ------- | -------- |
| BFS           | Explores level by level            | Yes     | Yes      |
| DFS           | Goes deep before backtracking      | No      | No       |
| UCS           | Expands lowest-cost node first     | Yes     | Yes      |
| DLS           | DFS with depth limit               | No      | No       |
| IDDFS         | Repeated DFS with increasing depth | Yes     | Yes      |
| Bidirectional | Searches from start and goal       | Yes     | Yes      |



---

## 📁 Project Structure

```
ai-pathfinder/
│
├── gui_main.py       # Main application and user interface
├── algorithms.py     # All search algorithm implementations
├── grid_model.py     # Grid and node data structures
├── requirements.txt  # Project dependencies
└── README.md         # Project documentation
```

---

 Color Legend

| Color  | Meaning           |
| ------ | ----------------- |
| Green  | Start node        |
| Red    | Target node       |
| Gray   | Wall/Obstacle     |
| Yellow | Frontier nodes    |
| Blue   | Explored nodes    |
| Purple | Final path        |
| Orange | Dynamic obstacles |

---

How It Works

1. Click to place the start point (green)
2. Click to place the target point (red)
3. Click to add **walls** (gray)
4. Press 1–6 to select an algorithm
5. Press SPACE to start visualization
6. Watch the algorithm explore and find the path

---

requirements.txt Content

```
pygame>=2.0.0
```

---

## 📜 License

MIT License – Free to use, modify, and distribute.
