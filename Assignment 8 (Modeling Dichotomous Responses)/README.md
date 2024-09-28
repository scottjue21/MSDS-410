# Assignment 8: Modeling Dichotomous Responses with Logistic Regression

## Overview
This analysis focuses on predicting whether a bottle of wine will be purchased based on its characteristics using a logistic regression model. The dataset contains approximately 12,000 observations, each representing a unique wine. The response variable, `Purchase`, indicates whether a wine was purchased (`1`) or not (`0`). As the response is dichotomous, logistic regression was chosen to model the probability of a wine being purchased. Key objectives of this analysis include assessing model fit, identifying significant predictors, and refining the model by removing variables that do not contribute to its predictive power.

## Methods and Techniques
The following methods and techniques were employed to develop and evaluate the logistic regression model:
- **Multicollinearity Testing**: Variance Inflation Factor (VIF) used to assess multicollinearity between predictor variables.
- **Model Selection**: Forward, backward, and stepwise model selection procedures used to optimize model performance.
- **Model Diagnostics**:
  - Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC) to compare models.
  - Analysis of Variance (ANOVA) and Chi-squared tests to assess the significance of predictor variables.
  - Cook’s Distance Chart to detect influential data points.
  - Box-Tidwell test to check for violations of the linearity assumption.
- **Model Evaluation**: 
  - Receiver Operating Characteristic (ROC) curve and Area Under the Curve (AUC) used to assess model performance.
  - Accuracy, sensitivity, and specificity metrics calculated.
  - Comparison of log-likelihoods before and after dropping variables to assess their impact on model performance.
  
## Key Findings
The final logistic regression model demonstrated that the **STARS rating** and **Acid Index level** were the strongest predictors of whether a wine was purchased. The STARS variable, initially a discrete rating (1-5), was transformed into a binary variable due to missing values for many observations. Additionally, several variables identified as statistically significant were found not to contribute meaningfully to the model’s predictive power and were removed for a more parsimonious model.

## Conclusion
The final model achieved high predictive accuracy and improved generalization by focusing on key predictors such as STARS and Acid Index levels. This analysis underscores the importance of simplifying models to improve interpretability and prevent overfitting, particularly in large datasets. The logistic regression model developed here provides valuable insights for wine manufacturers by highlighting characteristics that significantly influence purchasing behavior.

