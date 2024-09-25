# Exploratory Data Analysis (EDA) of Ames Housing Data

## Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Ames Housing dataset, which contains information on residential properties sold in Ames, Iowa between 2006 and 2010. The goal of this EDA is to better understand the dataset prior to building a linear regression model for predicting housing prices. Through this analysis, we explore the variables, assess data quality, and identify potential predictors for modeling.

The dataset, sourced from the Ames Assessor’s Office, includes detailed property characteristics and sale price data. This project provides a foundation for predicting future home sales by understanding key factors influencing property values.

## Key Objectives

- Gain a high-level overview of the dataset variables
- Assess data quality and identify any limitations
- Perform exploratory analysis to identify potential predictors for linear regression modeling
- Address skewness and outliers in the data
- Prepare the data for future modeling efforts

## Tools

- **Programming Language:** R
- **Libraries Used:** `ggplot2`, `dplyr`, and `tidyr` for data manipulation and visualization.

## Summary

The EDA uncovered important insights into the distribution and relationships between variables, particularly the response variable, `SalePrice`. Data quality checks revealed some outliers and variables with missing or irrelevant information, which required cleaning. Additionally, a logarithmic transformation was applied to `SalePrice` to correct its right-skewed distribution, while three key predictor variables were identified as normally distributed.

Further investigation into outliers and the creation of a representative sample population of "typical" homes will be crucial for building an accurate linear regression model.
