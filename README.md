```
python vacuum_search.py
```
![image](https://github.com/user-attachments/assets/9a72f61b-5092-4acf-a5bc-45545bd2e1e2)

Here’s a detailed and engaging project description for your GitHub README file:

---

# **Intelligent Vacuum Cleaner Simulator**

## **Project Overview**
The **Intelligent Vacuum Cleaner Simulator** is a Python-based application designed to showcase the implementation of advanced search algorithms for intelligent path planning in a fully observable grid environment. This project demonstrates the use of both **uninformed** and **informed search algorithms** to solve a real-world-inspired problem: optimizing a cleaning robot's path to clean all dirty cells while navigating obstacles and minimizing costs.

The project integrates concepts from **Artificial Intelligence (AI)**, including heuristic-based problem-solving, agent-based modeling, and graphical simulation. It features an interactive GUI that allows users to visualize the robot's decision-making process, path exploration, and cleaning performance.

---

## **Key Features**
1. **Interactive GUI**:
   - A graphical grid-based environment where users can visualize the robot's movement, obstacles, and dirt locations.
   - Customizable options to set the type of search algorithm, cost functions, and heuristics.

2. **Search Algorithms**:
   - **Uninformed Searches**:
     - **Breadth-First Search (BFS)**: Explores all possible paths uniformly.
     - **Depth-First Search (DFS)**: Dives deep into paths before backtracking.
     - **Uniform Cost Search (UCS)**: Selects paths based on cumulative cost.
   - **Informed Searches**:
     - **Greedy Search**: Uses heuristics like Manhattan or Euclidean distance to find the closest dirty cell.
     - **A * Search**: Combines path cost and heuristics for optimal performance.

3. **Cost Functions**:
   - **Step Cost**: Basic cost for each movement.
   - **StepTurn Cost**: Additional cost for turns, simulating real-world constraints.
   - **StayLeft and StayUp Costs**: Encourage cleaning the left or upper regions first, useful for prioritization scenarios.

4. **Performance Metrics**:
   - Tracks the **total path length**, **number of explored nodes**, and **cleaning cost** for each algorithm.
   - Real-time updates displayed on the GUI.

5. **Heuristic Analysis**:
   - Compare Manhattan and Euclidean heuristics to evaluate their impact on search efficiency.
   - Generate analysis reports to explain differences in explored and path counts.

---

## **How It Works**
The environment consists of:
- **Walls**: Represent obstacles the robot must navigate around.
- **Dirty Cells**: Target locations that the robot must clean.
- **Robot Agent**: Starts in the middle of the grid and plans its path to the nearest dirty cell using the selected search algorithm.

The robot operates as follows:
1. Selects a target dirty cell.
2. Plans its path using the chosen algorithm.
3. Moves to the dirty cell, cleans it, and repeats until all cells are clean.

Each move, turn, or action is logged and visualized, allowing users to understand the decision-making process in detail.

---

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**: 
  - `Tkinter`: For GUI creation.
  - `NumPy`: For numerical computations.
  - `collections`: For efficient data structures.
- **Search Algorithms**: Implemented from scratch to reinforce understanding of AI principles.

---

## **Installation and Usage**
### Prerequisites
- Python 3.x installed on your system.
- Required dependencies installed:
  ```bash
  pip install numpy
  ```

### Run the Project
1. Clone the repository:
   ```bash
   https://github.com/faa35/A1-AI.git
   ```
   ```
   cd A1-AI
   ```
2. Run the program:
   ```bash
   python vacuum_search.py
   ```
3. Use the GUI to:
   - Select algorithms (BFS, DFS, UCS, Greedy, A*).
   - Set cost functions and heuristics.
   - Visualize the robot's path and metrics.

---

## **Project Goals**
This project was developed as part of a course on Artificial Intelligence. It aims to:
1. Provide hands-on experience with implementing AI search algorithms.
2. Demonstrate the practical application of heuristics and cost functions.
3. Build an interactive simulation to visualize decision-making processes.

---



## **Assignment description**
see assignment docx for that

---
