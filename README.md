# Ant-Colony-Optimization-ACO-for-Traveling-Salesman-Problem-TSP-
This project uses Ant Colony Optimization (ACO) in Python to solve the Traveling Salesman Problem (TSP). It simulates ants finding the shortest path by updating pheromone trails, showing how teamwork and shared information can help solve complex routing problems.

Project Overview:
Ant Colony Optimization is a probabilistic technique inspired by the behavior of real ants seeking paths between their colony and food sources. This project implements ACO to solve the TSP, where the goal is to find the shortest possible route visiting each city exactly once and returning to the origin city.

Features:
  Flexible number of cities and ants.
  Real-time tracking of best path and pheromone updates.
  Visualization of pheromone matrices as heatmaps.
  Integration with Google Colab’s file download feature for exporting results.
  Modular functions to easily customize and extend the algorithm.


How It Works
  Generate Cities: A random distance map is created between cities.
  Drop Ants: Each ant starts at city 0 and visits all other cities.
  Choose Next City: Ants pick the next city based on pheromone strength and distance (closer cities and stronger trails are preferred).
  Complete the Tour: Ants return to the starting city after visiting all others.
  Update Pheromones: Paths with shorter distances get more pheromone added, while others fade over time.
  Repeat: This process runs for many iterations. Over time, ants follow better paths, and the best path is found.
