# Assignment 6: Regression Modeling with Variable Selection and Validation

## Overview
This project focuses on finalizing a linear regression model to predict SalePrice from the Ames, IA housing dataset. The analysis emphasizes feature selection and model validation using a train/test split. Both continuous and categorical variables were explored, with categorical variables encoded as dummy variables. Additionally, the right-skewed response variable, SalePrice, was log-transformed to improve model performance and back-transformed for interpretability.

## Data
The dataset was filtered to focus on single-family homes with residential zoning, normal sale conditions, and other criteria that align with a typical home in Ames. The final dataset consisted of 1,782 observations after removing outliers and observations that didn’t meet the defined sample population criteria.

## Methodology
Key techniques used in this project include:
- **Feature Selection**: Automated variable selection was combined with manual evaluation to refine the model. Variables were tested for multicollinearity using VIF values, and their predictive power was assessed by analyzing changes in R-squared when removing individual variables.
- **Dummy Coding** for categorical variables like Neighborhood.
- **Log Transformation** of SalePrice to address skewness.
- **Model Validation**: A train/test split was used (70% training, 30% testing) to evaluate model performance on unseen data.
- **Model Diagnostics**: The underlying assumptions of regression, including homoscedasticity and normality, were checked using standardized residuals and Cook’s distance charts. Outliers and influential observations were carefully handled to avoid overfitting.
- **Performance Metrics**: Adjusted R-squared, AIC, BIC, Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE) were used to assess the model's goodness of fit.

## Results
The final model explained approximately 89% of the variance in SalePrice (R-squared = 0.89) and achieved strong predictive accuracy, predicting sale prices within 10% of the actual values for about 70% of the observations. The log-transformation of SalePrice, followed by back-transformation for interpretation, improved model fit while maintaining interpretability in the business context.

## Conclusion
This project demonstrated the importance of thoughtful feature selection, model validation, and careful treatment of outliers. It highlighted the balance between achieving strong model fit and maintaining interpretability, particularly when working with transformations and dummy variables. The final model provided a practical approach for predicting housing prices with robust performance metrics, offering valuable insights into the Ames housing market between 2006 and 2010.
