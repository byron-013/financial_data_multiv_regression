# financial_data_multiv_regression
There are 2 folders in this file; here are their descriptions:

Folder#1 - Project- Linear Regression Functions (n variable):
This folder includes the files containing functions I made to perform linear regressions of n independent variables: built entirely from scratch without the use of any statistical libraries. The single variable linear regression model demonstrates a deep understanding of the mathematical concepts behind linear regression, including the calculation of slope and intercept using covariance and variance. It also showcases the ability to generate random datasets for regression analysis and visualize the results.

The multivariable linear regression model extends these concepts to multiple predictors. It calculates the coefficients and intercept of the regression model using the formula for multivariable linear regression and also calculates the predicted values and residuals. This model also demonstrates the ability to generate random datasets with multiple predictors and an understanding of the complexities involved in multivariable regression.

Both models showcase the ability to perform statistical analysis and data visualization, as well as the ability to generate and work with random datasets. These implementations are a testament to the understanding of fundamental data science concepts and the ability to apply them in Python. They also demonstrate the ability to modularize code and reuse components across different scripts, as seen in the use of the single variable regression model for plotting in the multivariable regression model. This repository is a great resource for anyone looking to understand the underlying mathematics of linear 
An expansion of COVID sector analysis project to include more variables. Is being used to make chatbot that walks through this type of regression. (link here when deployed - est 4/25/24).


Folder#2 - ECONOMICMULTI-VAR LINEAR REGRESSION PROJECT:
This folder contians a Python-based project which showcases a comprehensive approach to economic data analysis. The program begins by gathering a large set of economic data, which is then organized and cleaned for further processing. It leverages yfinance to calculate additional data given a ticker and a date range, generating a substantial file with 25 columns, each corresponding to a variable.

The program allows the user to choose which variables to use in a multivariable linear regression. It properly splits the data into training and test data and performs a diagnosis to identify if some variables need to be removed due to dependence or multicollinearity. It also conducts tests for heteroskedasticity and generates a variety of plots for a comprehensive understanding of the data.

The program offers the option to remove variables and provides guidance on how to transform the data to use a variable with multicollinearity or heteroskedasticity. It then presents the final regression and organizes all the data used at all steps for future reference. The program also indicates if a nonlinear model is needed.

In the final step, the program performs the final regression with your choice of variables and transformations and generates the corresponding plots. This is done on both the training and testing data. Any changes made to the training data are automatically applied to the test data to ensure consistency in the final run.
