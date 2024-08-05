# Sales Forecasting Using Multivariate Linear Regression on Advertising Data

## Project Overview

This project aims to build a predictive model that forecasts sales based on the money spent on different advertising platforms, using a multivariate linear regression approach. The dataset used for this analysis includes advertising expenditures across TV, radio, and newspapers.

## Problem Statement

The goal is to analyze the relationship between advertising spend and sales and to develop a model that accurately predicts sales based on these expenditures.

## Data

The dataset used is the advertising dataset from ISLR, which contains advertising expenses and corresponding sales figures. The features include:
- **TV advertising** expenditure
- **Radio advertising** expenditure
- **Newspaper advertising** expenditure
- **Sales** figures

## Steps Involved

1. **Reading and Understanding the Data:**
   - Importing necessary libraries
   - Loading the dataset
   - Initial data inspection and cleaning

2. **Exploratory Data Analysis (EDA):**
   - Univariate and bivariate analysis
   - Outlier detection and treatment
   - Visualizing relationships between features and target variable

3. **Model Building:**
   - Splitting the data into training and testing sets
   - Building a simple linear regression model
   - Building a multivariate linear regression model
   - Evaluating model performance using metrics such as R-squared, VIF, and more

4. **Model Evaluation:**
   - Testing the model on the test dataset
   - Comparing predicted values with actual sales figures

## Dependencies

```bash
- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- statsmodels
- scikit-learn
