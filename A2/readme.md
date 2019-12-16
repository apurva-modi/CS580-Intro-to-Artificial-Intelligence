## The Eggholder’s function
____

1. Optimization of a function with real parameters.
- Task 1. (Hill Climbing Search) (20 pts)
Implement a Hill Climbing (descending) algorithm to find the global minimum of the Eggholder’s function. Adopt a maximum step size of 1.0. A new position (x’, y’) can be generated from old position (x, y) by x’ = (rand() – 0.5)*0.1 + x and y’ = (rand() – 0.5)*1.0 + y, where rand() is a uniform random number generation function generating random numbers in [0, 1).
Randomly generate an initial position. Use the Hill Climbing algorithm to optimize the Eggholder’s function starting from the initial position. Terminate the optimization process when a better position yielding lower objective function value is not found in the last 100 steps. Repeat this process for 100 runs. Display the distribution of the minima you found in each run on a figure.

- Task 2. (Differential Evolution)	(20 pts)
Implement a Differential Evolution algorithm to find the global minimum of the Eggholder’s function. Terminate the optimization process when a better position yielding lower objective function value is not found in the last 100 steps. Repeat this process for 100 runs. Display the distribution of the minima you found in each run on a figure.

- Task 3. (Analysis) (10 pts)
Compare the results and computational time you obtain in the last two tasks. Draw your conclusions.
____
##  N-queens Problem
____
- Task 1. (Hill Climbing Search) (25 pts)
Implement a Hill Climbing Search algorithm to find a solution of the N-queens problem from a random given position. Use the number of pairwise attacks as the objective function.  Repeat the program 100 times for N = 8, N = 16, and N = 32 and show how many times you can find the solutions. Plot the initial state and the final state (not necessary the solution) of the first 10 times.

- Task 2. (Genetic Algorithm) (25 pts)
Implement a Genetic algorithm to find a solution of the N-queens problem. Use the number of pairwise attacks as the objective function. Repeat the program 100 times for N = 8, N = 16, and N = 32 and show how many times you can find the solutions.
