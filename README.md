# One-Variable-Linear-Regression
One Variable Linear Regression from Scratch using gradient descent and using scikit-learn

## Overview
This project demonstrates linear regression, gradient descent and squared error function from scratch and also using scikit learn for single variable.
This project uses a small dataset of student test scores and the amount of hours they studied.

**Gradient descent visualization**

<p align="center">
<img src="https://raw.githubusercontent.com/mattnedrich/GradientDescentExample/master/gradient_descent_example.gif" alt="gradient_descent_visualization" width="600"/>
</p>

**Sum of squared distances formula (to calculate our error)**

<p align="center">
<img src="https://spin.atomicobject.com/wp-content/uploads/linear_regression_error1.png" alt="sum_of_squared_distance_visualization" width="300"/>
</p>

**Partial derivative with respect to b and m (to perform gradient descent)**

<p align="center">
<img src="https://spin.atomicobject.com/wp-content/uploads/linear_regression_gradient1.png" alt="parcial_derivative_visualization" width="300"/>
</p>

## Dependencies

* numpy

Use `pip to install numpy` to install numpy. Works with Python 2.x and 3.x

## Execution

To execute Linear Regression from Scratch, just run the file using Python
```
python "Linear Regression from Scratch.py"
```

The output will look like this
```
Starting with m as 0 and b as 0 we get error 2782.5539172416056
Running....
After 1000 iterations, m as 1.472003357146311 and b as 0.2658134872230222 we get error 56.261600442221535
```

To execute Linear Regression using Scikit Learn, just run the file using Python
```
python "Linear Regression using Scikit Learn.py"
```

The output will look like this
```
We get m as 1.3381037220246799 and b as 7.221214607193161.
Mean squared error - 137.14657579981292.
```


