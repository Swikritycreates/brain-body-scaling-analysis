# Brain–Body Scaling in Mammals

This project analyzes the relationship between brain weight and body weight across mammalian species using regression modeling in R.

## Research Questions

- What is the relationship between body weight and brain weight in mammals?
- What is a plausible range for the scaling coefficient?
- Are humans outliers in this relationship?

## Methods

-Data cleaning and filtering (removal of invalid values)
-Linear regression and diagnostic checks
-Log–log transformation to satisfy model assumptions
-Confidence interval estimation for regression coefficients


## Key Findings

-Brain weight scales sublinearly with body weight (exponent ≈ 0.67)
-95% CI for scaling coefficient: 0.62 – 0.72
-Humans are a clear outlier, with significantly higher brain weight than predicted

## Tools Used

R
ggplot2, dplyr, broom, performance, equatiomatic
Quarto (.qmd)
