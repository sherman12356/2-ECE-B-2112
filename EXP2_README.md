# README for Experiment 2

## Project Overview

Two problems in this Jupyter Notebook are meant to help you practice using Python for array manipulation and normalization  with the use of NumPy, a potent Python library for numerical computation.

### Problem 1: Normalization

In this problem, you will:

* Create a 5x5 random ndarray.
* Normalize the ndarray by using the formula given.
* Save the normalized ndarray as X_normalized.npy.

### Problem 2: Divisible by 3

In this problem, you will:

* Create a 10x10 ndarray where each element is the square of the first 100 positive integers.
* Identify all elements in the array that are divisible by 3.
* Save the result as div_by_3.npy.

## Instructions
1. Normalization Problem

* Create a random 5x5 ndarray using np.random.random().
* Get the mean and standard deviation using .mean() and np.std() methods.
* Normalize the array using the formula:

Z=X-μ/σ

​ where X is the ndarray, μ is the mean, and σ is the standard deviation.
* Save the normalized ndarray using np.save('X_normalized.npy', X_normalized).


2. Divisible by 3 Problem

* Create a 10x10 ndarray using the squares of the first 100 positive integers: 
* Use modulus operator % to find elements divisible by 3.
* Save the result using np.save('div_by_3.npy', div_by_3).


## Usage
Open the Jupyter Notebook.
Follow the steps in each problem's section to execute the code.
Generated files X_normalized.npy and div_by_3.npy will be saved in the current working directory.
File Structure
Normalization_and_Array_Manipulation.ipynb: Jupyter Notebook containing the solution to both problems.
X_normalized.npy: Normalized 5x5 ndarray (output of Problem 1).
div_by_3.npy: Array of elements divisible by 3 from the 10x10 ndarray (output of Problem 2).

## Conclusion
This notebook shows how to normalize arrays and modify ndarrays using mathematical operations like as element-wise division and modulo.
