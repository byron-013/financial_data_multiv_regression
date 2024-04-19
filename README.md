# financial_data_multiv_regression
An expansion of COVID sector analysis project to include more variables. Is being used to make chatbot that walks through this type of regression. (link here when deployed - est 4/25/24).
This Python-based project showcases a comprehensive approach to economic data analysis. The program begins by gathering a large set of economic data, which is then organized and cleaned for further processing. It leverages yfinance to calculate additional data given a ticker and a date range, generating a substantial file with 25 columns, each corresponding to a variable.

The program allows the user to choose which variables to use in a multivariable linear regression. It properly splits the data into training and test data and performs a diagnosis to identify if some variables need to be removed due to dependence or multicollinearity. It also conducts tests for heteroskedasticity and generates a variety of plots for a comprehensive understanding of the data.

The program offers the option to remove variables and provides guidance on how to transform the data to use a variable with multicollinearity or heteroskedasticity. It then presents the final regression and organizes all the data used at all steps for future reference. The program also indicates if a nonlinear model is needed.

In the final step, the program performs the final regression with your choice of variables and transformations and generates the corresponding plots. This is done on both the training and testing data. Any changes made to the training data are automatically applied to the test data to ensure consistency in the final run.
