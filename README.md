# Univariate_linear_regression

## Objectives 

This Project focus on three learning objectives:

     1. Implement the gradient descent algorithm from scratch.
     
     2. Perform univariate linear regression with Numpy and Python.
     
     3. Create data visualizations and plots using matplotlib.
     
## Structure 

### Task 1: Introduction and Import Libraries

* Introduction to the data set and the problem overview.

* Import essential modules and helper functions from NumPy and Matplotlib.

### Task 2: Load the Data and Libraries

* Load the dataset using pandas.

* Explore the pandas dataframe using the head() and info() functions.

### Task 3: Visualize the Data

Before starting on any task, it is often useful to understand the data by visualizing it.
For this dataset, we can use a scatter plot using Seaborn to visualize the data, since it has only two variables: the profit and population.

### Task 4: Compute the Cost 𝐽(𝜃)

* Fit the linear regression parameters 𝜃 to our dataset using gradient descent.

* The objective of linear regression is to minimize the cost function J(𝜃).

-- You can think of the cost as the error your model made in estimating a value.

### Task 5: Implement Gradient Descent from scratch in Python

* In batch gradient descent, each iteration performs the following update.
With each step of gradient descent, the parameters 𝜃_j come closer to the optimal values that will achieve the lowest cost J(𝜃).

### Task 6: Visualizing the Cost Function J(𝜃)

* plot the cost over a 2-dimensional grid of 𝜃_0 and 𝜃_1 values.

The purpose of this graph is to show how J(𝜃) varies with changes in 𝜃_0 and 𝜃_1.
We can see that the cost function J(𝜃) is bowl-shaped and has a global minimum.

### Task 7: Plotting the Convergence

* plot how the cost function varies with the number of iterations.

* plot the J values against the number of iterations.

### Task 8: Training Data with Univariate Linear Regression Fit

* Use these parameters to plot the linear fit. 

### Task 9: Inference using the optimized 𝜃 values

* In this final task, let’s use our final values for 𝜃 to make predictions on profits in cities of 35,000 and 70,000 people. 
