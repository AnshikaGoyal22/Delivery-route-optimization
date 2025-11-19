# Delivery Route Optimization Project

This project models and solves a delivery route optimization problem using various algorithmic strategies. It includes visualization, profit analysis, and validity checks.

---

## Strategies Overview

### 1. Recurrence Relations
- **Description:** Uses recursive functions to estimate the total delivery route cost by exploring all possible sequences.
- **How it works:** It attempts all permutations; this approach demonstrates exponential complexity but guarantees optimal solutions for small instances.
- **Output:** Minimum route cost calculations and selected optimal sequence.

### 2. Greedy Algorithm
- **Description:** Selects parcels based on the highest value-to-weight ratio.
- **How it works:** Sorts parcels greedily; suitable for large datasets but may not always produce optimal routes.
- **Output:** Selected parcels, total profit, and route planning.

### 3. Dynamic Programming (DP)
- **Description:** Ensures delivery within time-windows using DP on the route scheduling.
- **How it works:** Discretizes time states to find feasible delivery sequences.
- **Output:** Schedule of deliveries fitting time windows and route costs.

### 4. Graph Algorithms (Dijkstra, MST)
- **Description:** Uses shortest path algorithms for routing and MST algorithms for network connectivity.
- **How it works:**
  - Dijkstra finds the minimal travel time from depot to each customer.
  - Prim’s MST connects all locations with minimal total distance.
- **Output:** Efficient routes, network graphs.

### 5. Travel Salesman Problem (TSP)
- **Description:** Finds the optimal visit sequence for small instances.
- **How it works:** Brute-force or Held-Karp DP; evaluates all permutations.
- **Output:** Optimal route path and total distance.

---

## How to Run

1. Clone or download the repository.
2. Open the `delivery_route_optimization.ipynb` in Google Colab or Jupyter Notebook.
3. Run all cells in order.
4. Visualize outputs and review the analysis sections for results.

---

## Output Explanation

- **Route Map:** Shows the delivery network and the optimized path on a graph.
- **Profit vs. Weight:** Visualizes how total parcel value changes with the total weight selected.
- **Delivery Success Rate:** Pie chart indicating the percentage of parcels delivered within their time windows.
- **Complexity and Time Profiling:** Insight into computation costs of different algorithms.

---

## Final Notes
- Adjust the routes and parcel selections based on your results.
- The notebook includes cells with explanations and visualizations, modeling real-world logistics challenges.

