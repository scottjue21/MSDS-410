# Comparing Linear Regression Models Assignment

## Overview
This assignment focuses on building and comparing various linear regression models using the Ames, Iowa housing dataset to predict the sale price of typical homes sold between 2006 and 2010. The analysis includes simple and multiple linear regression models, exploring how transformations and outlier detection/removal affect model performance. 

The dataset was filtered to a sample population of 1,782 observations based on criteria such as residential zoning, single-family homes, normal sale conditions, and additional constraints related to property characteristics like square footage and number of rooms. An outlier, identified through price per square foot, was removed to ensure the model accurately represents the majority of the sample population. 

Each regression model was evaluated based on its goodness of fit and adherence to the assumptions underlying linear regression models.

## Key Objectives
- Develop and compare multiple linear regression models to predict the sale price of homes.
- Investigate the effects of variable transformation and outlier removal on model performance.
- Evaluate each model's fit, check for assumptions, and assess the impact of model decisions such as transformations and outlier removal.

## Tools Used
- **Programming Language:** R
- **Techniques:** Simple linear regression, multiple linear regression, variable transformation, outlier detection and removal, model evaluation (goodness of fit), assumption checks (e.g., homoscedasticity).

## Summary
This analysis demonstrates how outlier removal and variable transformations can influence the results of regression models. While removing outliers can improve the model’s fit, it risks introducing bias by excluding legitimate data points that may be relevant for future predictions. Similarly, variable transformations can improve model assumptions, but they can also reduce the model’s interpretability, especially for non-technical audiences. Overall, the decisions surrounding transformations and outlier treatment should be made carefully, balancing model performance with interpretability and real-world applicability.
