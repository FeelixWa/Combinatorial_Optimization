# Combinatorial Optimization

This repository contains implementations of various combinatorial optimization algorithms, focusing on both graph algorithms and metaheuristic methods.

## Features

- **Graph Algorithms**: Implementations of BFS, DFS, and shortest path algorithms.
- **Metaheuristic Algorithms**: Methods for solving the knapsack problem, including Simulated Annealing, Tabu Search, and Ant Colony Optimization (ACO).

## Graph Algorithms

- **BFS & DFS**: Explore graph nodes level by level (BFS) or dive deep into paths (DFS). Useful for pathfinding and exploring connected components.
- **Shortest Path Algorithms**: 
  - **Unweighted Shortest Path**: Finds the shortest path using BFS.
  - **DAG Relaxation**: Computes shortest paths in Directed Acyclic Graphs.
  - **Bellman-Ford**: Handles graphs with negative weights, detecting cycles.
  - **Dijkstra**: Efficient for graphs with non-negative weights.

## Metaheuristic Algorithms

### Knapsack Problem

The knapsack problem is tackled using several metaheuristic approaches, each implemented with a focus on feasibility and solution quality.

1. **Simple Descent Method**: Iterative improvement by exploring feasible neighbors.
2. **Simulated Annealing**: Probabilistic search that allows uphill moves to escape local optima.
3. **Tabu Search**: Keeps track of visited solutions to avoid cycles.
4. **Ant Colony Optimization (ACO)**: Mimics the behavior of ants searching for food to find optimal solutions.

