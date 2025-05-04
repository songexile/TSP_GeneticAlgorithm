# TSP Solver using Genetic Algorithms

The Traveling Salesman Problem (TSP) is a classic optimisation problem where the goal is to find the shortest possible route that visits each city exactly once and returns to the origin city. This implementation approaches the TSP using genetic algorithms, which mimic natural selection to evolve solutions over generations.

The project implements a genetic algorithm with the following components:

Population Initialization: Random permutations of city indices
Fitness Evaluation: Total distance of the route
Selection: Tournament selection to choose parents for breeding
Crossover: Order-based crossover operators designed for permutation problems
Mutation: Swap mutation with configurable probability
Replacement: Generational replacement with elitism
