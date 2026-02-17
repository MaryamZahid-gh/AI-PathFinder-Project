AI Pathfinder – Visual Search Algorithms
A Python visualization tool for uninformed search algorithms using Pygame. Watch BFS, DFS, UCS, DLS, IDDFS, and Bidirectional Search explore a grid in real-time.
Features
•	6 search algorithms with step-by-step visualization
•	Interactive grid for setting start, target, and obstacles
•	Real-time statistics: nodes explored, path length, frontier size, execution time
•	Adjustable visualization speed
•	Dynamic obstacles spawning during search
•	Pause / Resume, Reset, and Clear Path controls
Installation
Requirements
•	Python 3.7+
•	Pygame 2.0+
Setup
git clone https://github.com/MaryamZahid-gh/AI-PathFinder-Project
cd ai-pathfinder
pip install -r requirements.txt
Running the App
python gui_main.py
Controls
Action	Control
Select algorithm (BFS–Bidirectional)	1–6
Start / Pause visualization	SPACE
Reset search	R
Clear grid	C
Adjust speed	+ / -
Exit app	ESC
Place points & walls	Mouse Click

Algorithms
Algorithm	Description	Optimal	Complete
BFS	Breadth-First Search	Yes	Yes
DFS	Depth-First Search	No	No
UCS	Uniform-Cost Search	Yes	Yes
DLS	Depth-Limited Search	No	No
IDDFS	Iterative Deepening DFS	Yes	Yes
Bidirectional	Two-way search	Yes	Yes
Optimal for uniform costs
Project Structure
ai-pathfinder/
├── gui_main.py       # Main application and UI
├── algorithms.py     # Search algorithm implementations
├── grid_model.py     # Grid and Node data structures
└── README.md         # This file

Color Legend
Color	Meaning
Green	Start
Red	Target
Gray	Wall
Yellow	Frontier nodes
Blue	Explored nodes
Purple	Final path
Orange	Dynamic obstacles

How It Works
1.	Click to place start point (green)
2.	Click to place target point (red)
3.	Click to add walls (gray)
4.	Press 1–6 to select an algorithm
5.	Press SPACE to visualize the algorithm
6.	Watch the algorithm find the path!
Dependencies
Install manually:
pip install pygame
Or via requirements.txt:
pip install -r requirements.txt
requirements.txt
pygame>=2.0.0
License
MIT License – See code for details
