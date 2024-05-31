# unified-differential-evolution
Object Oriented Implementation of Unified Differential Evolution and Standard Numerical Optimisation Benchmark Functions

Differential Evolution (DE) is a metaheuristic, population-based evolutionary algorithm for the global optimisation of nonlinear and non-differentiable continuous space functions. In this notebook I apply a unified version of DE for application on a range of standard benchmark functions which are frequently found in literature. The suite contains functions of varying natures e.g. modality, seperability etc. so that subsequent DE performance analysis is comprehensive. This Unified Differential Evolution (UDE) approach is inspired by a paper by Ji Qiang and Chad Mitchell and can be used for global optimisation of functions across the test suite. Within this notebook I also give from-scratch implementations of Random Search (RS) and Stochastic Hillclimbing (SHC). Using these search algorithm classes and benchmark functions one can compare the behaviour and performance of different heuristic approaches in different optimisation scenarios. Efficient UDE operation hinges on proper tuning of DE schema and parameters such as crossover rate (CR).

References:

JI Qiang. 2014. A unified differential evolution algorithm for global optimization. (2014)

Ji Qiang, Chad Mitchell, and Albert Qiang. 2016. Tuning of an adaptive unified differential evolution algorithm for global optimization. In 2016 IEEE Congress on EvolutionaryComputation(CEC). https://doi.org/10.1109/CEC.2016.7744305
