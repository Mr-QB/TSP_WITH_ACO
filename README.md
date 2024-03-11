# Solving the Traveling Salesman Problem (TSP) with Ant Colony Optimization (ACO)

## Introduction
In real-world scenarios, the traveling salesman problem (TSP) is an important and widely studied optimization problem. ACO is a metaheuristic algorithm based on the self-organizing behavior of ants and is widely used to solve this problem.

## Installation
The code in the [TSP_with_ACO.ipynb](TSP_with_ACO.ipynb) file provides a simple implementation of the ACO algorithm to solve the TSP. To run the program, you need to have Python installed along with the matplotlib and numpy libraries. You can install these libraries by running the following command:

```pip install matplotlib numpy```

## Usage
1. Edit the parameters in the [TSP_with_ACO.ipynb](TSP_with_ACO.ipynb) file to meet the requirements of the problem:
   - `num_cities`: Number of cities in the problem.
   - `num_ants`: Number of ants (solutions) to be tried.
   - `iterations`: Number of iterations of the algorithm.
   - `alpha`: Alpha coefficient, the influence of pheromones on choosing the next city.
   - `beta`: Beta coefficient, the influence of distance to the next city.
   - `decay_factor`: Decay factor, the coefficient for pheromone evaporation after each iteration.
   - `Q`: Q parameter, necessary for updating the pheromone matrix.

2. Run the program by executing the code cells in [TSP_with_ACO.ipynb](TSP_with_ACO.ipynb).

## Results
After running, the program will display the best path found by the ACO algorithm along with the corresponding distance.

## Extensions
You can extend the program by experimenting with different parameters, tweaking the ACO algorithm, or adding new features such as more complex visualizations.