# unified-differential-evolution
Repository contains object oriented implementation of Unified Differential Evolution (UDE) inspired by a paper by Ji Qiang and Chad Mitchell. The notebook also contains from-scratch implementations of simple Random Search (RS) and Stochastic Hillclimbing (SHC) algorithms. Furthermore, a range of standard benchmark functions used in numerical optimisation literature are included with literature-standard bounds e.g. Rosenbrock, Ackley, Schwefel, Rastrigin, and Greiwank.

Differential Evolution (DE) is a metaheuristic, population-based evolutionary algorithm for the global optimisation of nonlinear and non-differentiable continuous space functions. In this notebook I apply a unified version of DE for application on a range of standard benchmark functions which are frequently found in literature. The suite contains functions of varying natures (e.g. modality) so that subsequent DE performance analysis is comprehensive. This UDE approach is inspired by a paper by Ji Qiang and Chad Mitchell. [1][2] Using these search algorithm classes and benchmark functions one can compare the behaviour and performance of different heuristic approaches in different optimisation scenarios. Efficient UDE operation hinges on proper tuning of DE schema and parameters such as crossover rate (CR).

References:

[1] JI Qiang. 2014. A unified differential evolution algorithm for global optimization. (2014)

[2] Ji Qiang, Chad Mitchell, and Albert Qiang. 2016. Tuning of an adaptive unified differential evolution algorithm for global optimization. In 2016 IEEE Congress on EvolutionaryComputation(CEC). https://doi.org/10.1109/CEC.2016.7744305
