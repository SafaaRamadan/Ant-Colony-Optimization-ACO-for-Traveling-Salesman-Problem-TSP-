# Ant-Colony-Optimization-ACO-for-Traveling-Salesman-Problem-TSP-
This project uses Ant Colony Optimization (ACO) in Python to solve the Traveling Salesman Problem (TSP). It simulates ants finding the shortest path by updating pheromone trails, showing how teamwork and shared information can help solve complex routing problems.

What is Ant Colony Optimization?
ACO is a nature-inspired metaheuristic algorithm based on the behavior of real ants searching for the shortest path between food sources and their nest. It uses simulated pheromone trails and probabilistic movement to explore paths, update knowledge, and converge to optimal or near-optimal solutions.

Features
  - ACO implementation for TSP from scratch using NumPy.
  - Tracking of best paths and costs per iteration.
  - Snapshot of pheromone matrices every 10 iterations.
  - Heatmap visualizations using Seaborn and Matplotlib.
  - Downloadable heatmaps for reports or presentations.

How It Works
  - Generate a Distance Matrix: Cities are randomly generated with distances between them.
  - Initialize Pheromones: All edges start with equal pheromone levels.
  - Simulate Ants: Each ant builds a tour based on pheromone and distance.
  - Update Pheromones: Trails are updated using a combination of evaporation and reinforcement.
  - Track Best Path: The best path and cost are recorded at each iteration.
  - Visualize: Every 10 iterations, a pheromone matrix snapshot and heatmap are saved.

Future Improvements
  - Add GUI for city selection.
  - Allow loading real-world city data.
  - Optimize parameters like alpha, beta, and evaporation rate.
  - Add animation for pheromone updates.

Acknowledgments
    Inspired by real-world behavior of ant colonies and classical ACO research. 
