# Introduction

## introduction to genetic algorithms

A Machine learning algorithm/technique used to find good, sometimes, optimal solution to search-based problems.

To be clear, all problems in theory are just a search-based problems and have a huge space of possible solutions.
Genetic algorithm search for the solution in this space by generating candidate solutions which belong to that space.

Genetic algorithms uses constraints and rules provided in order to find the optimal solutions to the problem at hand. Each constraint blocks certain amount of solutions from being offered which narrows down the size of the space it looks into.

## Goal oriented problem solving

For this algorithm to work, the engine must have a feedback, better than right or wrong feedback. This feedback is an indicator to how the solution fits the desired result. Ironically, it's called the fittness function.

The true goal of the engine is to (maximize and/or minimize) the fittness.

The engine can randomly generate solutions, or the programmer can use problem-specific knowledge to help eliminate number of combinations, or rather guide the algorithm to create better candidate solutions making it faster.

The engine stops in one of the following conditions:

1. Known solution is found.
2. Solution meeting all requirements is found.
3. Certain number of generations has passed.
4. Specific amount of time has passed.
5. Some other condition the programmer saw fit.
