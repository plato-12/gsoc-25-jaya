# GSoC 2025: Enhancing the Jaya R Package for Efficient Optimization

This repository contains my submissions for the easy and medium tasks for the "Enhancing the Jaya R Package for Efficient Optimization" project under Google Summer of Code 2025.

## Task Submissions

### Easy Task
The easy task involved installing and demonstrating the usage of the current Jaya package for optimizing a simple optimization problem.

- [Optimization of the Rosenbrock Function Using the Jaya Algorithm](easy.pdf) - A comprehensive R Markdown document demonstrating the application of the Jaya algorithm to minimize the Rosenbrock function, a classic non-convex benchmark function in optimization.

### Medium Task
The medium task required proposing a specific feature or algorithm improvement for inclusion in the package with a clear justification of its value.

- [Proposal for Jaya R Package Enhancement: Constraint Visualization](medium.pdf) - A detailed proposal for enhancing the Jaya package with constraint visualization capabilities for multi-objective optimization problems.

## Proposal Overview

My medium task submission proposes adding constraint visualization functionality to the Jaya R package to help users understand how constraints affect the solution space in multi-objective optimization. The enhancement includes:

1. An enhanced multi-objective optimization function (`jaya_multi_enhanced`) that tracks constraint information throughout the optimization process
2. A constraint visualization function (`plot_jaya_constraints`) that shows the Pareto front, feasible/infeasible solutions, and constraint boundaries

This enhancement would provide several key benefits:
- Better understanding of how constraints shape the available solution space
- Improved decision-making by visualizing trade-offs between objectives under constraints
- Enhanced sensitivity analysis capabilities
- Educational value for students and practitioners

## Hard Task Implementation

Based on this proposal, I've implemented a working prototype of the constraint visualization functionality in a separate repository: [jaya-enhancement](https://github.com/plato-12/jaya-enhancement).

The implementation includes:
- Full working code for the proposed functions
- Comprehensive documentation
- Unit tests
- A detailed vignette demonstrating real-world applications
- Successful build with no Errors/Warnings/Notes via win-builder
