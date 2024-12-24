# SCA_VRP

This code solves the Capacitated Vehicle Routing Problem (CVRP) using the PuLP optimization library and visualizes the results. It includes the following steps:

1. Setup and Data Preparation: Imports necessary libraries, sets parameters (customer count, vehicle count, vehicle capacity), and reads input data from a CSV file.
   
2.Distance Calculation: Defines a function to calculate the distance between each pair of customers using the Haversine formula.

3.Optimization Problem Definition: Uses PuLP to define the linear programming problem, including objective function and constraints.

4.Solving the Problem: Iterates over possible vehicle counts to find the minimum number required to satisfy constraints, including maximum route distance.

5.Result Extraction and Visualization: Extracts the optimal routes, creates a DataFrame for display, and visualizes the routes using Matplotlib and Folium.
