# Genetic Knapsack (Avoska:)

Solver for [one dimensional knapsack problem](https://en.wikipedia.org/wiki/Knapsack_problem) 
using [genetic algorithms](https://en.wikipedia.org/wiki/Genetic_algorithm)

# Usage

1. Knapsack (avoska) holds fruits.
2. Knapsack has a weight limit.
3. Each item (fruit) has weight and value (tastiness).
4. The program tries to determine which items to include in the collection so that the total weight is less than or 
   equal to a given limit and the total value is as large as possible. 
5. This is done using genetic algorithm:
   1. The goal is to optimize fitness. Fitness is GYYYYM. no. When solution has larger total value (and weight < limit) 
      it has larger fitness.
   2. The program generates a list (population) of (possibly) random solutions (creatures (cats)).
   3. The evolution starts, during which the following procedures are applied for fixed amount of iteration:
      1. Selection
      2. Genetic operators (Crossover or Mutation)
      3. Heuristics (optional)
   4. This way, the average fitness will have increased by this procedure for the population