# Polynomial Interpolation in Python

## Overview
This repository contains Python code demonstrating polynomial interpolation using two different methods: Lagrange interpolation and Newton interpolation. Polynomial interpolation is a numerical technique used to approximate a function by fitting a polynomial curve through a set of given data points.

## Contents
- `polynomial_interpolation.ipynb`: Jupyter Notebook containing the Python code demonstrating Lagrange and Newton polynomial interpolation.
- `README.md`: Summary of the project and instructions for usage.

## Usage
1. Clone the repository to your local machine.
2. Ensure you have Jupyter Notebook installed along with necessary dependencies such as NumPy, SciPy, and Matplotlib.
3. Open the `polynomial_interpolation.ipynb` notebook in Jupyter Notebook.
4. Follow the instructions within the notebook to execute the code cells and visualize the results.
5. Experiment with different sets of data points and interpolation methods to observe variations in the interpolating polynomials.

## Description
The notebook begins by defining functions for computing divided differences and coefficients required for Newton's polynomial interpolation. It then generates a set of data points from a trigonometric function y = sin(x) in the range [0,π/2].


The code proceeds to calculate the interpolating polynomials using both Lagrange and Newton interpolation methods. Finally, it plots the interpolating polynomials alongside the original data points, allowing for comparison of their behavior and accuracy.

## References
- Python Numerical Methods: [Chapter 17.05 - Newton's Polynomial Interpolation](https://pythonnumericalmethods.berkeley.edu/notebooks/chapter17.05-Newtons-Polynomial-Interpolation.html)
- Documentation for libraries used: NumPy, SciPy, Matplotlib
