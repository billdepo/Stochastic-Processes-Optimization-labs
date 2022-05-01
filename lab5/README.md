Based on: http://www.physics.rutgers.edu/~haule/681/src_MC/python_codes/salesman.py  

This lab explores the topics of:
- Hill-Climbing algorithm
- Simulated Annealing

for finding solutions of the famous TSP (Travelling Salesman Problem). 
The problem gets very complex when the number of cities the salesman needs to 
visit get over 20 and hence it's computationally inefficient or impossible
to find the optimal solution. However, we want to get as close as possible
in an efficient manner.

A complete solution means that all decision variables are specified. Algorithms 
on complete solutions manipulate one complete solution
at a time and when a better solution
is found the previous solution is replaced.
The algorithmic description of this idea is the following:
1. Initialise best solution.
2. Generate a solution x according to the specifics of the algorithm.
3. If x is better than best, replace best by x.
4. Repeat steps 2-3.
5. 
The next examples are examples for “algorithms on complete solutions” (unrelated to specific problems)
and NOT examples of “complete solutions” for specific problems.
Examples of algorithms on complete solutions:

- exhaustive search 
- local search 
- hill-climbing
- gradient-based optimisation methods
- simulated annealing 
- tabu search 
- genetic algorithms 