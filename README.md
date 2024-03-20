# Linear Regression Practice Lab
ASSIGNMENT 2 - QUESTION

## Intro

***Github Link*** : [https://github.com/Qmumu/ml_lab1](https://github.com/Qmumu/ml_lab1)
  
***Medium Link*** : [https://medium.com/@751153214/practice-lab1-linear-regression-d166c5db2685](https://medium.com/@751153214/practice-lab1-linear-regression-d166c5db2685)

## Project Overview

The goal of this project is to assist the CEO of a restaurant franchise in identifying potential cities for opening a new outlet by predicting profits based on city population data. The project involves implementing linear regression from scratch, including computing the cost function and performing gradient descent to learn the model parameters.

## Dataset

The dataset contains two variables:
- `x_train`: The population of a city (in 10,000s).
- `y_train`: The profit of a restaurant in that city (in $10,000s).

## Implementation Details

1. **Linear Regression Refresher**: We start with a brief overview of linear regression, focusing on the model prediction equation \(f_{w,b}(x) = wx + b\) and the cost function \(J(w,b)\).

2. **Compute Cost**: The implementation of the `compute_cost` function allows us to calculate the cost \(J(w,b)\) for a given set of parameters, helping us monitor the progress of gradient descent.

3. **Gradient Descent**: The `compute_gradient` function computes the gradient of the cost function with respect to the parameters \(w\) and \(b\), which are then used in the `gradient_descent` function to update the parameters and minimize \(J(w,b)\).

## Results

By running gradient descent with a suitable learning rate and number of iterations, we find the optimal parameters \(w\) and \(b\) that minimize the cost function. We then use these parameters to plot the linear fit against our training data, illustrating how well our model predicts profits based on city population.

## Predictions

The model can make profit predictions for new cities based on their populations. For example, we predict profits for cities with populations of 35,000 and 70,000 people, demonstrating the model's practical application in selecting new restaurant locations.

## Conclusion

This project successfully implements a linear regression model to predict restaurant profits from city population data. The findings can aid in strategic decision-making regarding the expansion of the restaurant franchise to new cities.
# ml_lab2
