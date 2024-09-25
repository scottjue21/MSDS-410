# Assignment 3: Multiple Linear Regression

## Overview
This project focuses on using the Ames, Iowa housing dataset to develop two multiple linear regression models aimed at predicting the sale price of a typical home in Ames between 2006 and 2010. The analysis leverages a refined subset of the original data based on predefined criteria, such as selecting only single-family homes in residential zones, normal sale conditions, and homes with a total square footage under 4,000. Homes missing data and those without public utilities or at least a 1-car garage were excluded to ensure data completeness before fitting the models.

The first model, referred to as **Model 3**, is a reduced model that uses a single category of explanatory variables. The second model, **Model 4**, builds on Model 3 by including additional explanatory variables. To validate the models, various statistical tests, including hypothesis testing, were conducted to determine the significance of the variables. A comparison of the two models was also performed to evaluate which model provided a better fit for predicting sale prices.

## Key Objectives
- Develop two multiple linear regression models to predict home sale prices:
  - **Model 3:** A reduced model with a focus on interior size variables.
  - **Model 4:** A more comprehensive model including additional variables, such as lot size.
- Perform hypothesis tests on the explanatory variables to evaluate their significance in predicting sale price.
- Conduct a nested F-test to compare the reduced model (Model 3) and the full model (Model 4).
- Determine which model better explains the variability in home sale prices.

## Tools Used
- **Programming Language:** R
- **Techniques:** Multiple linear regression, R-squared, adjusted R-squared, hypothesis testing on regression coefficients, F-test, nested F-test

## Summary
In this assignment, two multiple linear regression models were created to predict the sale price of homes in Ames, Iowa. **Model 3**, the reduced model, included only interior size variables. **Model 4**, the expanded model, added lot size variables and was found to be a better fit for the dataset, as confirmed by a nested F-test. The results indicate that adding more explanatory variables improves the model's ability to predict home sale prices more accurately.
