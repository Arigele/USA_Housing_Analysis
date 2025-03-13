# Extensive Data Analysis and Housing Price Prediction on 'usa_housing_kaggle (1).csv'

This project performs an extensive data analysis on the 'usa_housing_kaggle (1).csv' dataset, focusing on understanding the relationships between various features and housing prices. It also includes a housing price prediction model and provides investment insights based on the analysis.

## Table of Contents

- [Introduction](#introduction)
- [Data Analysis](#data-analysis)
- [Housing Price Prediction](#housing-price-prediction)
- [Trend Analysis](#trend-analysis)
- [Investment Insights](#investment-insights)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Introduction

The 'usa_housing_kaggle (1).csv' dataset contains information about housing properties in the USA. This analysis aims to:

- Explore the dataset and understand the distributions and correlations of various features.
- Build a linear regression model to predict housing prices.
- Analyze trends between key features and prices.
- Provide investment insights based on the model and analysis.

## Data Analysis

The data analysis part of the script performs the following tasks:

- **Data Loading:** Reads the CSV file into a Pandas DataFrame.
- **Data Exploration:**
  - Displays the first few rows of the DataFrame.
  - Provides basic information about the DataFrame (data types, non-null counts).
  - Generates summary statistics of the numerical columns.
- **Visualizations:**
  - Creates a correlation heatmap to visualize the relationships between numerical features.
  - Generates histograms for all numerical columns to understand their distributions.
  - Creates a scatter plot of 'Price' vs 'SquareFeet' to visualize their relationship.
  - Generates a boxplot of 'Price' by 'Bedrooms' to see the distribution of prices across different bedroom counts.
  - Creates a distribution plot for 'Price'.
  - Creates a scatter matrix to visualize pairwise relationships between all numerical features.

## Housing Price Prediction

A linear regression model is trained to predict housing prices based on selected features. The process involves:

- **Feature Selection:** Selecting relevant features for the model (e.g., 'Bedrooms', 'Bathrooms', 'SquareFeet', 'YearBuilt', 'GarageSpaces', 'LotSize', 'CrimeRate', 'SchoolRating').
- **Data Splitting:** Splitting the data into training and testing sets.
- **Model Training:** Training a linear regression model on the training data.
- **Prediction:** Predicting housing prices on the test data.
- **Evaluation:** Evaluating the model using Mean Squared Error (MSE) and R-squared (R²) metrics.
- **Visualization:** Plotting actual vs. predicted prices.

## Trend Analysis

The trend analysis focuses on understanding the relationship between 'YearBuilt' and 'Price' using a regression plot.

## Investment Insights

Based on the regression coefficients, the script provides insights into which features have the most significant impact on housing prices. It also discusses the implications for potential real estate investments.

## Dependencies

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (sklearn)
- Numpy

You can install the required packages using pip:

```bash
pip install pandas matplotlib seaborn scikit-learn numpy
