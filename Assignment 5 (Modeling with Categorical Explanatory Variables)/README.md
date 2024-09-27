# Assignment 5: Regression Models with Categorical Variables

## Overview
This project analyzes data from a nutrition study to develop several regression models using categorical variables as explanatory variables to predict cholesterol levels. The dataset consists of 16 variables and 315 observations, with 4 categorical variables: Smoke, Gender, VitaminUse, and PriorSmoke. The data was filtered to include smoking and non-smoking adults aged 19 to 83, who consume 4,000 calories or less and have a Beta Plasma level greater than 0, resulting in 312 observations for analysis.

Dummy variables were created for the categorical variables to be used in the regression models. The **Gender** variable was recoded (0 for female, 1 for male), and **Smoke** was also recoded (0 for No, 1 for Yes). Additionally, dummy variables were created for the levels of **VitaminUse** and **PriorSmoke**, and the **Alcohol** variable was transformed into categorical levels representing None, Some, and A Lot of alcohol consumption.

## Techniques
- **Multiple Linear Regression** models with categorical variables
- **Dummy Variable Encoding** for categorical variables
- **Interaction Terms** to assess variable relationships
- **ANOVA** (Analysis of Variance) for comparing model variances
- **F-test** for assessing the overall model significance
- **R-Squared** and **Adjusted R-Squared** for evaluating model fit
- **Standardized Residuals** to check model assumptions
- **Cook's Distance** chart for detecting influential observations
- **Hypothesis Testing** to assess variable significance

## Summary
In this analysis, multiple linear regression models were built using categorical variables, with dummy variables encoding categorical data for prediction. The primary goal was to determine whether categories had different mean cholesterol levels and explore interactions between categorical and continuous variables. The Gender variable provided the most predictive value when combined with the continuous variable Fat.

Through ANOVA and F-tests, the significance of the regression models was evaluated, and model performance was measured using R-Squared and Adjusted R-Squared. Outliers and influential data points were assessed using Cook's Distance, while standardized residuals were analyzed to ensure model assumptions were met.
