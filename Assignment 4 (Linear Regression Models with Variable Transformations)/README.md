# Assignment 4: Comparing Linear Regression Models with Variable Transformations

## Overview
This project analyzes the Ames, IA housing dataset to build and compare various linear regression models that predict the sale price of a typical home in Ames between 2006 and 2010. Through previous exploratory data analysis, the dataset was filtered to include only observations that fit the criteria for a "typical" home, such as being located in a residential zone, having single-family home types, normal sale conditions, and excluding extreme outliers in terms of price per square foot. The sample population after filtering and outlier removal consisted of 1,782 observations.

The focus of this analysis was to build both simple and multiple linear regression models using continuous explanatory variables, explore variable transformations, detect and remove outliers, and evaluate how these adjustments impact model performance.

## Techniques
- **Simple Linear Regression** and **Multiple Linear Regression** models
- **Variable Transformation** for homoscedasticity
- **Outlier Detection and Removal** to improve model fit
- **F-Test** to compare nested models
- **R-squared** and **Adjusted R-squared** for goodness of fit
- **Hypothesis Testing** for assessing model significance
- **DFFITS Plot** to detect influential points
- **ANOVA Table** for comparing model variances
- **Standardized Residuals** to evaluate model assumptions

## Summary
This analysis demonstrates how outlier removal and variable transformations can influence the results of regression models. While removing outliers can improve the model’s fit, it risks introducing bias by excluding legitimate data points that may be relevant for future predictions. Similarly, variable transformations can improve model assumptions, but they can also reduce the model’s interpretability, especially for non-technical audiences. Overall, the decisions surrounding transformations and outlier treatment should be made carefully, balancing model performance with interpretability and real-world applicability.


