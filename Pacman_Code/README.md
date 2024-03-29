# Pacman Project

The Pacman project is to create an AI-based Pacman agent that could navigate via a maze to collect food from a specified location. Implemented various search algorithms – depth-first, breadth-first, uniform cost, and A*, while maintaining admissibility and consistency. Implemented minmax and expectimax search algorithms to optimize routes against ghost-ridden area.  

The details of this Pacman project: [**Link**](https://sites.wustl.edu/amtabakhi/project1-search-2/).

The codes that we wrote are in 2 files - search.py and searchAgents.py, where the 4 search algorithms (DFS, BFS, uniform cost, A*) are implemented in search.py.

In searchAgents.py, we mainly completed 2 classes.The first one is CornersProblem class where Pacman agent could find paths through all four corners of a layout. We implemented the code by selecting a suitable state space and successor function. The second class is the foodSearchProblem class, where the Pacman agent finds a path that collects all of the food (dots) in a Pacman game. In both class we implemented consistent heuristics using mazeDistance() function to ensure correctness.   


