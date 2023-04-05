# Travelling Salesman Problem

This repository contains an implementation of the Travelling Salesman Problem (TSP) in Python. TSP is a classic optimization problem where the goal is to find the shortest possible route that visits every city in a given list exactly once and returns to the starting city. It is a well-known problem in computer science and has many real-world applications such as logistics, transportation planning, and DNA sequencing.

## Requirements

To run the program, you need to have `Python3` installed on your system. You can download Python from the official website at https://www.python.org/downloads/. In addition, the following Python packages are required:

* numpy
* matplotlib

You can install these packages by running the following command in the terminal:

```
pip3 install numpy matplotlib
```
## Usage

To run the program, clone the repository and navigate to the project directory in your terminal. Then run the following command:

```
python3 Travelling Salesman Problem.py
```

This will generate a plot of the shortest possible route that visits every city exactly once and returns to the starting city. The cities and their coordinates are defined in the cities.txt file. You can modify this file to test the program with different sets of cities.

## Approach
The program uses a brute-force approach to solve the TSP problem. It generates all possible permutations of the cities and calculates the total distance of each route. The shortest route is then selected as the solution. While this approach is not efficient for large numbers of cities, it provides an exact solution to the problem.

## Future Improvements
There are several ways to improve the efficiency of the program for larger numbers of cities. One approach is to use a heuristic algorithm such as the nearest neighbor or the 2-opt algorithm. Another approach is to use a genetic algorithm or simulated annealing to find a near-optimal solution.

