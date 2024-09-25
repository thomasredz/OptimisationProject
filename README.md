# Portfolio Optimization Using Frank-Wolfe Algorithms

## Overview

This repository contains the code and research paper related to the project titled **"Portfolio Optimization: Development and Comparative Analysis of Frank-Wolfe Algorithms on Real-World Data"**, submitted to the University of Padua. The project explores the application of several variants of Frank-Wolfe algorithms, including the **Away-Step Frank-Wolfe** and **Projected Gradient Methods**, in solving portfolio optimization problems. These methods are tested using real-world financial datasets.

## Project Structure

- **`5 FW Portfolio-1/`**: Useful paper for a deeper understanding of the project.
- **`data/`**: Includes the datasets used in the project, which consist of historical data from various stock indices like FTSE100, EURO STOXX 50, and FTSE MIB.
- **`Gabriele_Rosso_Code.ipynb`**: Jupyter notebook containing the Python implementation of the portfolio optimization algorithms (Frank-Wolfe, Away-Step Frank-Wolfe, and Projected Gradient Descent).
- **`Gabriele_Rosso_Paper.pdf`**: The research paper that provides the theoretical background, the implementation details, and the results of the project.
- **`README.md`**: This file, providing a high-level overview of the project.
- **`README.txt`**: A text-based version of the project description.

## Methods Implemented

1. **Projected Gradient Descent**: An optimization method for constrained problems that combines gradient descent with a projection step to ensure the solution stays within the feasible region.
   
2. **Frank-Wolfe Algorithm**: A classic optimization method for convex problems. This algorithm iteratively finds a solution by solving a linear subproblem, avoiding the need for computationally expensive projections.

3. **Away-Step Frank-Wolfe Algorithm**: A variant of the Frank-Wolfe method that improves convergence by introducing steps that move away from certain atoms, useful when the solution lies on the boundary of the feasible region.

## Datasets

The following datasets were used for portfolio optimization:

- **FTSE100**: 63 assets from the UK stock market, spanning from January 2007 to May 2013.
- **EURO STOXX 50**: 32 assets from European stock markets, with data from the same period.
- **FTSE MIB**: 34 assets from the Italian stock market, also covering the period from 2007 to 2013.

## Key Insights

- The **Frank-Wolfe** and **Away-Step Frank-Wolfe** algorithms showed superior performance in portfolio optimization tasks, particularly when using a line search step size strategy.
- The **Projected Gradient Descent** method, while effective, struggled with slow convergence in certain scenarios, particularly with large datasets or when using diminishing step sizes.
- The value of the risk-aversion parameter (`η`) significantly impacts portfolio composition, with higher values leading to more conservative portfolios focused on minimizing risk.

## How to Run the Code

1. Clone the repository.
2. Ensure that the required Python libraries are installed (refer to the Jupyter notebook for specific dependencies).
3. Open `Gabriele_Rosso_Code.ipynb` and run the cells to execute the portfolio optimization algorithms on the provided datasets.
