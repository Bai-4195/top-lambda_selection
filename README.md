# top-lambda_selection

# Overview
Top-lambda selection is a computational framework for the Shapley value (SV) based sensitivity analysis on the policy-augmented Bayesian network (PABN) model in the context of biomanufacturing. It aims to identify a subset of important random factors/high-quality data points in terms of their influence on the output variance.

# toy-network
The SV-based sensitivity is applied to a toy setup of PABN network. 
The source code of 5 algorithms for factor selection and data valuation based on linear Gaussian PABN model:
- ApproShapley
- gHL-based Algorithm
- Algorithm 1 (designed for factor selection)
- ALgorithm 3 (designed for data valuation)
- Theoretical SV calculation

# case-study
The SV-based sensitivity is applied to the multiphase fermentation process of Yarrowia lipolytica.
- factor selection: The original experimental data, ApproShapley, gHL-based Algorithm, Algorithm 1, Theoretical SV calculation
- gHL-based Algorithm: The experiment setup based on data, ApproShapley, gHL-based Algorithm, Algorithm 3, Theoretical SV estimation
