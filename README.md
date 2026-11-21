BIT 2118: Scientific Computing

Project Introduction

This repository contains Python programs prepared for the BIT 2118 Scientific Computing course. It demonstrates different numerical techniques using NumPy, SciPy and Matplotlib. The examples are based on practical problems in science, engineering, computing and data analysis.

Project Contents

The repository covers Tasks 2–20:

Task| Topic| Python Program
2| NumPy Arrays and Numerical Calculations| "Task_02_numpy_arrays.py"
3| Mathematical Functions and Vectorization| "Task_03_vectorization.py"
4| Floating-Point Operations and Numerical Errors| "Task_04_numerical_errors.py"
5| Matrix Algebra and Operations| "Task_05_matrix_algebra.py"
6| Solving Linear Equations| "Task_06_linear_systems.py"
7| Gaussian Elimination and LU Decomposition| "Task_07_gaussian_lu.py"
8| Iterative Techniques for Linear Systems| "Task_08_iterative_linear.py"
9| Eigenvalues and Eigenvectors| "Task_09_eigenvalues.py"
10| Bisection and Fixed-Point Techniques| "Task_10_bisection_fixed_point.py"
11| Newton-Raphson and Secant Techniques| "Task_11_newton_secant.py"
12| Polynomial and Nonlinear Equations| "Task_12_nonlinear_equations.py"
13| Interpolation Methods| "Task_13_interpolation.py"
14| Curve Fitting and Approximation| "Task_14_curve_fitting.py"
15| Numerical Differentiation| "Task_15_numerical_differentiation.py"
16| Numerical Integration| "Task_16_numerical_integration.py"
17| Euler Method for Differential Equations| "Task_17_euler_ode.py"
18| Solving ODEs with SciPy| "Task_18_scipy_ode.py"
19| Numerical Optimization| "Task_19_optimization.py"
20| Random Numbers and Monte Carlo Simulation| "Task_20_monte_carlo.py"

Software Requirements

To run the programs, the following are needed:

- Python 3.10 or a newer version.
- NumPy for numerical calculations.
- SciPy for scientific and mathematical methods.
- Matplotlib for creating graphs and visualizations.

All required libraries are listed in the "requirements.txt" file.

Installing the Required Libraries

Open a terminal in the project folder and execute:

python -m pip install --upgrade pip
python -m pip install -r requirements.txt

For Windows users who use the Python launcher, run:

py -m pip install --upgrade pip
py -m pip install -r requirements.txt

To check whether the libraries have been installed correctly, use:

python -c "import numpy, scipy, matplotlib; print(numpy.__version__, scipy.__version__, matplotlib.__version__)"

Executing the Programs

Each task can be run separately from the project directory. For example:

python Task_16_numerical_integration.py

Some programs produce graphical results using Matplotlib. A graph window will appear when such a program is executed.

To check the Python files for syntax errors, run:

python -m compileall .

Overview of the Tasks

Tasks 2–5: Numerical Computation and NumPy

- Task 2: Uses NumPy arrays to analyze temperature readings and calculate their average, highest and lowest values. It also converts temperatures from Celsius to Fahrenheit.
- Task 3: Shows how vectorization can process large amounts of data faster than ordinary Python loops.
- Task 4: Explains how rounding and floating-point precision can affect mathematical calculations.
- Task 5: Uses matrices to perform scaling and rotation of two-dimensional coordinates.

Tasks 6–9: Matrix Operations and Linear Algebra

- Task 6: Uses NumPy to find unknown values in a system of simultaneous linear equations.
- Task 7: Demonstrates Gaussian elimination and LU decomposition when solving linear systems.
- Task 8: Implements Jacobi and Gauss-Seidel methods and compares their results with a direct solution.
- Task 9: Calculates eigenvalues and eigenvectors to determine the relative importance of nodes in a network.

Tasks 10–15: Numerical Methods and Equation Solving

- Task 10: Applies bisection and fixed-point iteration to determine an equilibrium temperature.
- Task 11: Uses Newton-Raphson and secant methods to calculate an investment's internal rate of return.
- Task 12: Finds solutions to nonlinear equations using SciPy.
- Task 13: Estimates unknown values between existing measurements using linear interpolation and cubic splines.
- Task 14: Uses curve fitting to study the relationship between the number of users and server response time.
- Task 15: Estimates the speed of a moving vehicle using recorded GPS positions and numerical differentiation.

Tasks 16–20: Integration, Differential Equations and Simulation

- Task 16: Calculates electrical energy consumption using trapezoidal and Simpson's integration methods.
- Task 17: Applies Euler's method to study how the temperature of a hot object changes as it cools.
- Task 18: Uses SciPy to solve an ordinary differential equation and model voltage changes in an RC circuit.
- Task 19: Applies numerical optimization to find a cost-effective allocation of server resources.
- Task 20: Uses random numbers and Monte Carlo simulation to estimate the probability of server overload.

Project Requirements and Documentation

For each task, the following activities should be completed:

1. Identify the input data and values used in the program.
2. Describe the mathematical method or calculation being applied.
3. Change at least one input value or parameter and explain the difference in the results.
4. Describe the program's output and explain any graphs produced.
5. Adapt the original program to address another related real-life problem. Include the assumptions, new data, results and explanations.

Possible Areas for Further Application

The numerical methods demonstrated in this project can also be applied to other situations, including:

- Studying humidity measurements instead of temperature readings.
- Applying matrix transformations in robotics and computer graphics.
- Predicting temperature changes in buildings.
- Calculating vehicle distance using speed measurements.
- Improving resource allocation in computer networks.
- Estimating the likelihood of network failures through simulation.

Conclusion

This project provides practical experience in applying numerical methods through Python programming. It develops an understanding of mathematical computations, problem-solving techniques, data analysis and graphical representation of results using scientific computing libraries.
