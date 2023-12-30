# Implementation-of-GAs-on-VRP
The project implements a Genetic Algorithm (GA) for solving the Vehicle Routing Problem (VRP) using Python. The VRP involves optimizing routes for multiple vehicles to serve a set of customers while minimizing total travel distance. The program sets parameters such as the number of customers and vehicles, the population size, mutation rate, and number of generations for the genetic algorithm.
It creates an initial population of routes, evaluates fitness based on total distance traveled, and employs tournament selection, ordered crossover (OX), and mutation to evolve better solutions across generations. The algorithm aims to find the most efficient routes for vehicles to serve all customers and return to the depot.
The code uses a distance matrix computed from geographical coordinates of locations in South West Delhi to represent distances between customers. It visualizes the best route found by the algorithm on a plot, showcasing the optimal path for vehicles to traverse through all specified locations.
This project demonstrates how genetic algorithms can efficiently solve complex optimization problems like the VRP by iteratively evolving better solutions based on the principles of natural selection and genetic crossover.
