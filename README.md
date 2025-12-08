## Project 3 in FYS-STK4155

Project authors: Amund Solum Alsvik, Jørgen Vestly & Kristoffer DH Stalker  

This repository contains all source code and figures for our research, using PINNs for solving the 1D heat diffusion equation. 
To run the code, run the Jupyter notebooks, and the classes.py file.

---  
### Contents   

**Code**  
The Code folder contains:

- classes.py: Contains the PINN class, also contains heatmap test code for different activation functions and optimizers.  
- functions.py: contains all utilities related to the project, such as forward Euler algorithm and analytical solution.
- imports.py: contains all imports needed for the running the code.
- The following test files in jupyter notebooks, useful for benchmarking and as setup examples:  
  - tests.ipynb: contains, in principle all test code for the forward Euler algorithm, but also 3D animations for our solution.
  - tests_d.ipynb: contains test code for model selection of PINN, meaning finding the best set of hyperparameters yielding the best performance.
  - tests_helper.ipynb: contains additional testcode for doing nonlinear least squares, and various model comparisons
  - classes.py: has test for different network configuration based on activation functions and optimizers.
 
**Figures**
The Figure folder contains all relevant plots with informative prefixes.

All required packages to run the code, are listed in requirements.txt

In the LLM folder, we have added links to our LLM chats (see LLM/links.md).
