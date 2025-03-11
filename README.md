# TASK 4 OPTIMIZATION MODEL

Author: Bisma yb


Domain:Data Science


# OPTIMIZATION-MODEL

## Overview

This project demonstrates a simple Linear Programming (LP) optimization model using Python and PuLP. The goal is to maximize an objective function under given constraints.

### Problem Statement

A fleet of 2 vehicles must serve 5 customer locations + 1 depot while minimizing travel distance. Each vehicle has a maximum capacity constraint.

## Objective: Minimize total distance traveled.

#### Constraints:

Each customer is visited exactly once.

Vehicle capacity must not be exceeded.

Each vehicle must start and return to the depot.

Implementation Details

Decision Variables: x[i][j][v] (1 if vehicle v travels from location i to j)

Objective Function: Minimize travel distance based on a predefined distance matrix

Constraints: Ensure vehicle capacity is maintained and all customers are served.

Solver: PuLP’s optimizer is used to find an optimal route assignment.

