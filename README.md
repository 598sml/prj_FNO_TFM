# prj_PDE_Find

This project aims to use Symbolic Regression for PDE Find. 

The workflow is as follows: 

1. Use traditional numerical methods to create ground truth data

2. Corrupt it with added Gaussian Distributed Noise to create syntheatic experimental data 

3. Extract the variables, and their spatial and temporal derivatives using neural networks (Residual Attention Neural Networks is used here)

4. Get physical expression (Use a python symbolic regression package called pysr)

5. Compare the coefficients with the original set-up

6. Put the newly constructed governing equations back to the numerical solvers to recreate the graphs 
