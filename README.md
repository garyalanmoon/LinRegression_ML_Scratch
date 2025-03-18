This program implements linear regression from scratch.
**(1) Generate synthetic data**
Select the number of instances m and features n.
Generate a random array X from standard normal distribution.
Select random "true" weights using uniform distribution.
Generate target via y = Xw + noise.

**(2) Exploratory data analysis**
Visualize the data via histograms and scatterplots.
Print summary statistics of the data.

**(3) Split into training/testing sets**
A custom function is written to split the dataset into training and testing datasets with the user defining the size of the testing set.
This function is called to split the data into training and testing sets.

**(4) Set up the model**
Define functions to make predictions given weights, compute the loss function (MSE) and compute the gradient of the loss function.
Define a function to run gradient descent with a user-prescribed learning rate until (i) change in loss is below a prescribed tolerance or
(ii) a maximum number of iterations is exceeded.

**(5) Make predictions and evaluate the model**
Make predictions on the training set and evaluate performance by looking at RMSE, R^2 and other measures of error.
