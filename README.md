# AI ESSENTIALS

This project implements **classical AI search algorithms** in **Java**, including **Uniform Cost Search (UCS)**, **A* Search** (with and without Manhattan distance heuristic), and **Minimax** for game decision-making.

---

## TABLE OF CONTENTS
1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Input Data](#input-data)
5. [Algorithms Implemented](#algorithms-implemented)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Output Files](#output-files)
9. [Testing](#testing)
10. [License](#license)
11. [Contact](#contact)

---

## OVERVIEW

This project demonstrates the **implementation of classical AI search algorithms** in Java for solving pathfinding and decision-making problems.

It includes:
- **Uniform Cost Search (UCS)** for optimal pathfinding  
- **A* Search** with and without Manhattan heuristic  
- **Minimax Algorithm** for two-player decision-making  

These algorithms are **foundational in AI** for solving **graph search and game problems** efficiently.

---

## FEATURES

- **Uniform Cost Search (UCS)** to find the optimal path in a weighted graph  
- **A* Search** with:
  - Standard implementation without heuristics
  - Manhattan distance heuristic for grid-based pathfinding  
- **Minimax Algorithm** for simple two-player adversarial games  
- **Console-based outputs** for algorithm steps and results

---

## PROJECT STRUCTURE

```
ai-essentials/
│── README.md
│
└── src/
    ├── UCS.java                     # Uniform Cost Search implementation
    ├── AStar_with_Manhattan.java    # A* Search with Manhattan heuristic
    ├── AStar_Without_Manhattan.java # A* Search without heuristic
    └── MINIMAX.java                 # Minimax algorithm implementation
```

---

## INPUT DATA

- **Graph or Grid** for UCS and A* search
  - Nodes with edge costs for UCS
  - Grid representation for Manhattan A*
- **Game Tree / States** for Minimax
  - Structured as parent-child nodes with evaluation scores

*(Modify or extend inputs according to the problem you want to solve.)*

---

## ALGORITHMS IMPLEMENTED

1. **Uniform Cost Search (UCS)**
   - Expands the **least-cost node first**
   - Guarantees **optimal solution**

2. **A* Search**
   - **Without Manhattan:** Acts as Dijkstra's when heuristic = 0
   - **With Manhattan:** Uses |x1-x2| + |y1-y2| heuristic for grid paths

3. **Minimax Algorithm**
   - Classical **two-player game tree search**
   - Computes **optimal move** assuming opponent plays perfectly

---

## INSTALLATION

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/ai-search-algorithms.git
cd ai-search-algorithms
```

2. **Install Java (>= 11)**

3. **Compile the Java files:**
```bash
javac src/*.java
```

---

## USAGE

Run any algorithm from the command line:

### **1. Uniform Cost Search**
```bash
java -cp src UCS
```

### **2. A* Search**
```bash
java -cp src AStar_Without_Manhattan
java -cp src AStar_with_Manhattan
```

### **3. Minimax Algorithm**
```bash
java -cp src MINIMAX
```

*(Adjust main methods or input files according to your testing setup.)*

---

## OUTPUT FILES

- Console output showing **expanded nodes, paths, and costs**
- **Optional log files** can be added to capture step-by-step execution

---

## TESTING

- Verify **UCS** on a weighted graph with known optimal path  
- Verify **A\*** on grid pathfinding problems (check Manhattan heuristic improves efficiency)  
- Verify **Minimax** on small game trees where the **optimal move is known**  

---

## LICENSE

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## CONTACT

**Christos Gkovaris**  
University of Ioannina – Computer Science and Engineering  
[GitHub](https://github.com/ChristosGkovaris)