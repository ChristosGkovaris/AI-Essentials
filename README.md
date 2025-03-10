# AI Essentials
Welcome to the "AI Essentials" repository. This repository contains the implementation of several fundamental AI algorithms in Java. The repository includes four major algorithms: UCS, A* with Manhattan heuristic, A* without Manhattan heuristic, and MINIMAX.



## Overview
**UCS (Uniform Cost Search)**
- Objective: Solve the 8-puzzle problem by finding the optimal solution path with minimal 
  movement cost. UCS explores nodes based on their cumulative path cost, 
  ensuring the most cost-effective solution.

**AStar with Manhattan Distance**
- Objective: Solve the 8-puzzle problem using A* search with the Manhattan distance as the 
  heuristic function. This heuristic measures the minimum number of moves 
  needed by summing the horizontal and vertical distances of tiles from their goal positions.

**AStar without Manhattan Distance**
- Objective: Solve the 8-puzzle problem using A* with a simpler heuristic, counting the number 
  of misplaced tiles. This approach estimates the distance to the goal 
  state by tallying how many tiles are out of place.

**MINIMAX**
- Objective: Implement a basic AI player using the Minimax algorithm for a game based on 
  maximizing or minimizing points in a 3x3 board game scenario. The AI player aims 
  to predict and counter the opponent’s moves to achieve optimal gameplay outcomes.



## Implementation Details
- The **UCS** and **A*** algorithms for the 8-puzzle problem utilize priority queues and sets 
  to manage the explored and frontier states, ensuring efficiency in 
  pathfinding.
- The **Minimax** algorithm uses a recursive approach and memoization to determine optimal 
  moves for maximizing and minimizing players, analyzing potential board states 
  for the best move.



## Collaboration
This project was a collaborative effort. Special thanks to [SpanouMaria](https://github.com/SpanouMaria) for their significant contributions to the development and improvement of the project.
