# Assignment 7: Logistic Regression Analysis: Predicting ICU Survival Probability

## Overview

This project focuses on constructing a logistic regression model to predict the probability of survival for patients admitted to an adult Intensive Care Unit (ICU). The dataset consists of 200 randomly selected subjects from a larger study on ICU patient outcomes in a major metropolitan area. The target response variable, `STA`, is a dichotomous variable indicating survival (STA = 0) or non-survival (STA = 1), making logistic regression the appropriate modeling technique. This analysis explores the relationship between predictor variables (e.g., Age, Admission Type) and the likelihood of survival, using conditional probability, odds, and the logit transformation to fit the model.

## Key Analysis Techniques

- **Contingency Table**: Explored the relationship between categorical variables and survival outcomes.
- **Probability & Odds Ratio Calculations**: Estimated the odds and probabilities of survival for different predictor variables.
- **Logistic Regression Model**: Developed to predict the probability of ICU patient survival using Age and other variables.
- **Hypothesis Testing**: Conducted a likelihood-ratio test to evaluate the statistical significance of the fitted model.
- **Model Evaluation**: Assessed model fit using:
  - **AIC** (Akaike Information Criterion)
  - **BIC** (Bayesian Information Criterion)
  - **Deviance** (Log-likelihood based measure)
  
## Summary

The analysis revealed that age alone was not a strong predictor of ICU survival, as the predicted probabilities remained under 0.5 across all age groups. This result aligns with the fact that even older patients had survival probabilities greater than 50%. The model did not exhibit the typical 'S' shaped curve for predicted probabilities, suggesting that other variables (beyond age) may need to be considered to improve model performance and discrimination. This analysis provided a foundational understanding of logistic regression, introducing important concepts such as converting probabilities to odds, interpreting model fit statistics, and conducting hypothesis tests.
