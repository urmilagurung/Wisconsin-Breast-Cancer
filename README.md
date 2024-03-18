# Wisconsin Breast Cancer

## Overview
This report presents an analysis of the Wisconsin Breast Cancer Database using various statistical and machine learning techniques implemented in R.

## Data Preprocessing
- **Data Cleaning**: Removal of NA values and redundant observations.
- **Data Conversion**: Recoding of 'class' variable and conversion of factors to quantitative variables.

## Exploratory Data Analysis
- **Tumor Class Distribution**: Visualization of the distribution of tumor classes.
- **Descriptive Statistics**: Calculation of mean and standard deviation for the dataset.

## Statistical Analysis
- **Variance-Covariance Matrix**: Examination of the relationship between variables.
- **Correlation Matrix**: Analysis of the correlation between response variables.

## Model Building
- **Logistic Regression**: Implementation of logistic regression with best subset selection based on AIC and BIC.
- **LASSO Regression**: Application of LASSO regression for variable selection and model tuning.
- **Linear Discriminant Analysis (LDA)**: Utilization of LDA for classification.

## Model Evaluation
- **Validation Sets**: Assessment of model performance using validation sets.
- **Cross-Validation**: Application of 10-fold cross-validation for LDA and logistic regression models.

## Conclusion
The report concludes with insights drawn from the statistical analysis and model evaluations, contributing to the understanding of breast cancer data patterns.

## Dependencies
- R packages: `knitr`, `mlbench`, `tidyverse`, `ggplot2`, `bestglm`, `glmnet`, `MASS`, `nclSLR`
