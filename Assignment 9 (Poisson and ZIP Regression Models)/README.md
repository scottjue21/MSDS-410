# Assignment 8: Predicting Stressful Events in Adolescents Using Poisson and Zero-Inflated Poisson Regression Models

## Project Overview
This project explores the application of Poisson and Zero-Inflated Poisson (ZIP) regression models to predict the number of stressful life events (STRESS) experienced by adolescents in the U.S. The dataset includes responses from 651 adolescents, with explanatory variables like family cohesion (COHES), self-esteem (ESTEEM), prior year’s grades (GRADES), and school attachment (SATTACH). The main objective was to assess which model best fits the data and identify the most important predictors of stressful events in adolescents. This analysis evaluated several models, including Poisson, ZIP, OLS, and logistic regression models, to determine which approach provided the most accurate predictions.

## Key Methods and Techniques
- **Modeling Techniques**: Poisson Regression, Zero-Inflated Poisson (ZIP) models, Ordinary Least Squares (OLS) Regression, Logistic Regression
- **Variable Selection**: Forward, backward, and stepwise selection methods were applied, along with comparison using AIC, BIC, and chi-squared tests.
- **Model Diagnostics**: Residuals were analyzed for heteroscedasticity vs. homoscedasticity patterns. Multicollinearity was checked using VIF values. Model fit was assessed using goodness-of-fit metrics such as the deviance, AIC, and BIC.
- **Model Interpretation**: Exponentiation was applied to the coefficients for clearer interpretation of the changes in odds for each explanatory variable. 
- **Model Comparisons**: Confusion matrix, ROC curve, and AUC were generated to evaluate model performance. Chi-square tests were used to compare models when variables were removed.
  
## Conclusion
The analysis showed that the ZIP model was the best fit for predicting the number of stressful events, compared to other models. Although the OLS regression explained only 8% of the variance, and logistic regression helped predict whether stress was present, the ZIP model best represented the data's distribution. The Poisson model improved prediction for stressful events but was limited in its ability to predict adolescents with no stress. The ZIP model provided a more accurate representation of the actual stress distribution, though it struggled with predicting zero-stress cases. Overall, the ZIP model offered the best balance between predicting the presence and count of stressful events, making it the most suitable approach for this dataset.
