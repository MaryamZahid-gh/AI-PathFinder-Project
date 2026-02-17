AI Pathfinder – Visual Search Algorithms

A Python visualization tool for uninformed search algorithms using Pygame. Watch BFS, DFS, UCS, DLS, IDDFS, and Bidirectional Search explore a grid in real-time.

---Features

* 6 search algorithms with step-by-step visualization:

  * BFS (Breadth-First Search)
  * DFS (Depth-First Search)
  * UCS (Uniform-Cost Search)
  * DLS (Depth-Limited Search)
  * IDDFS (Iterative Deepening DFS)
  * Bidirectional Search
* Interactive grid for setting:

  * Start node
  * Target node
* Real-time statistics:

  * Nodes explored
  * Path length
  * Frontier size
  * Execution time
* Adjustable visualization speed
* Pause / Resume, Reset, and Clear controls

---

Requirements

* Python 3.7+
* Pygame 2.0+

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

### Step 3: Install Dependencies

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
| Place start and target               | Mouse Click |

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

Optimal for uniform costs.

---

Project Structure

```
ai-pathfinder/
├── gui_main.py       # Main application and UI
├── algorithms.py     # Search algorithm implementations
├── grid_model.py     # Grid and Node data structures
├── requirements.txt  # Project dependencies
└── README.md         # Project documentation
```

---

Color Legend

| Color  | Meaning        |
| ------ | -------------- |
| Green  | Start node     |
| Red    | Target node    |
| Yellow | Frontier nodes |
| Blue   | Explored nodes |
| Purple | Final path     |

---

## How It Works

1. Click to place the start point (green)
2. Click to place the target point (red)
3. Press 1–6 to select an algorithm
4. Press SPACE to start visualization
5. Watch the algorithm explore and find the path

---

requirements.txt Content

```
pygame>=2.0.0
```

---

License

MIT License – Free to use, modify, and distribute.
