# Informed-And-Uninformed-Search-Algorithms-Implementation
This project focuses on exploring various AI search algorithms, both uninformed and informed, to tackle a problem involving agent movement, food consumption, and achieving optimal paths. The primary goal is to implement and compare these algorithms for solving the given problem.

## Problem Description
We have a map with `n` rows and `m` columns, featuring an agent at the starting point (0, 0). The map also contains food, medicines, and blocked cells, which the agent cannot traverse. If the agent reaches a cell with medicine, a new agent will appear at the cell (n-1, 0). The objective is to consume all the food and medicines while navigating all agents to the endpoint (n-1, m-1), finding the optimal path.

## Algorithms

### Informed Search Algorithms
- **A\* (A-Star):** An informed search algorithm that utilizes heuristic functions to determine the most promising path to the goal state.

### Uninformed Search Algorithms
- **BFS (Breadth-First Search):** Utilizes only the information from the problem definition to traverse the search space.
- **IDS (Iterative Deepening Depth-First Search):** An uninformed search strategy that combines depth-first search's space efficiency and breadth-first search's completeness.
## Objectives

This project involves the following objectives:
1. Define the terms 'Agent' and 'State' in the context of AI search strategies.
2. Implement A\* (A-Star) algorithm.
3. Implement BFS (Breadth-First Search).
4. Implement IDS (Iterative Deepening Depth-First Search).
5. Define a heuristic function.
6. Define an evaluation function.


Through these objectives, we aim to explore and apply a range of AI search algorithms for the given problem, gaining insights into their performance and effectiveness.
