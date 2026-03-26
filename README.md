Maze Solver Using Depth First Search (DFS)

This project implements a Maze Solver using the Depth First Search (DFS) algorithm with a graphical user interface. The program allows users to visualize how DFS explores a maze step-by-step to find a path from the start point to the goal.

Algorithm Visualization in C#

Overview
This project demonstrates how the Depth First Search (DFS) algorithm can be applied to solve a maze problem. The maze is represented as a grid, where the algorithm explores possible paths until it reaches the target cell or determines that no solution exists.

The application includes a graphical interface that visually shows the solving process in real time.

Features
Character-Based Grid Representation: The maze is stored as a 2D grid
DFS Algorithm Implementation: Uses a stack to simulate recursive DFS
Step-by-Step Visualization: Shows how the algorithm explores and backtracks
Interactive Maze Editing: Users can click on cells to add or remove walls
Random Maze Generation: Generates a new maze with random obstacles
Reset Functionality: Restores the original maze state
Status Display: Shows current solving state (ready, solving, solved, no solution)

How It Works
The maze is initialized as a 2D grid with walls and paths
The algorithm starts from the initial cell (top-left area)
A stack is used to explore neighboring cells using DFS
Each move is visualized in real time:
- Active path is highlighted
- Dead ends are backtracked
The algorithm continues until:
- The goal is reached, or
- All possible paths are exhausted

Installation & Usage

Prerequisites
Visual Studio
.NET Framework (Windows Forms support)
