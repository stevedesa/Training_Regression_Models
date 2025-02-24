# Project 1: Understanding and Training Regression Models

## Introduction

This project explores the application of regression models to analyze and model relationships between input variables. The primary focus is on implementing and comparing different regression techniques, including gradient descent and analytic solutions, to understand their effectiveness in predicting outcomes based on real-world datasets.

## Objectives

- Implement and compare regression models to analyze datasets.
- Understand the relationship between input variables and target outputs.
- Gain hands-on experience with optimization techniques such as gradient descent, stochastic gradient descent, and normal equations.
- Evaluate model performance using Mean Squared Error (MSE) and visualize results.

---

## Datasets

1. **MovieData.csv**: Contains critic scores and audience scores for movies.
2. **HousingData.csv**: Contains housing prices as a function of size (square footage) and year built.

---

## Implementation

### Problem A: Linear Regression on Movie Data

- **Objective**: Predict audience scores based on critic scores using linear regression.
- **Steps**:
  1. Load and visualize the dataset.
  2. Implement Mean Squared Error (MSE) calculation.
  3. Implement gradient descent to learn model parameters.
  4. Implement an analytic solution for linear regression.
  5. Compare the results of gradient descent and the analytic solution.
  6. Split the data into training and testing sets (80/20 split) and evaluate model performance using MSE.

### Problem B: Linear Regression on Housing Data

- **Objective**: Predict housing prices based on size and year built using a linear model.
- **Steps**:
  1. Load and visualize the 3D dataset.
  2. Implement a linear regression model using the analytic solution.
  3. Plot the model surface alongside the original data to visualize the fit.

### Problem C: Complex Model on Housing Data

- **Objective**: Improve the model fit by introducing a more complex model.
- **Steps**:
  1. Transform the input features to fit a non-linear model.
  2. Learn the model parameters using the analytic solution.
  3. Compare the MSE of the complex model with the linear model.
  4. Visualize the complex model's fit using a 3D surface plot.

---

## Results

### Problem A: Movie Data
- **Test Set MSE**: 327.25  
- **Conclusion**: Both gradient descent and the analytic solution yielded similar regression lines, confirming the correctness of the implementations.

### Problem B: Housing Data (Linear Model)
- **Learned Parameters**:  
  - \( w_0 = -64835.13 \)  
  - \( w_1 = 0.19 \)  
  - \( w_2 = 33.01 \)  
- **MSE**: 30171.90  

### Problem C: Housing Data (Complex Model)
- **MSE**: 2476.08  
- **Conclusion**: The complex model significantly outperformed the linear model, achieving a much lower MSE.

---

## Dependencies

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
