# CA01-EDA_House_Price_Perdiction
Exploratory Data Analysis and Data Cleaning for Housing Price Data

# Project Overview

This project performs Exploratory Data Analysis (EDA) and data cleaning on a housing price dataset. The goal is to understand the structure and quality of the dataset and prepare it for future machine learning models that can predict housing prices.

EDA is the first step in any data science workflow. It helps researchers explore patterns, identify data issues, and understand relationships between variables before building predictive models. 

# CA01_EDA_House_Price_Perdiction…

The final outcome of this project is a clean and analytics-ready dataset suitable for house price prediction models.

# Dataset

The dataset contains various features that may influence housing prices.

Examples of variables include property characteristics such as:

Lot size
Number of rooms
Property age
Location attributes

Structural features

# Dataset source:

House Price Dataset
https://github.com/ArinB/MSBA-CA-Data/tree/main/CA01

Files included:

house-price-train.csv (used for this analysis)

house-price-test.csv

data_description.txt

For this assignment, only the training dataset is used for EDA and data cleaning.

# Project Objectives

The main objectives of this project are:

Understand the structure and distribution of the dataset

Identify data quality issues such as missing values and outliers

Clean and transform the dataset to make it suitable for modeling

Analyze relationships between variables

Identify potential multicollinearity among features

# Methodology

The project follows the standard EDA workflow.

1. Data Understanding

In this step, the dataset structure and statistical properties are examined.

Tasks performed:

Review dataset dimensions and column types
Generate descriptive statistics
Perform univariate analysis
Perform bivariate and multivariate analysis
Create visualizations to understand data distribution
Identify data quality issues
A Data Quality Report is produced to summarize problems found in the dataset.

2. Data Cleaning and Preprocessing

Based on the data quality report, necessary cleaning steps are applied.

Tasks include:

Handling missing values
Detecting and treating outliers
Encoding categorical variables
Checking data consistency
Ensuring the dataset is analytics-ready
These steps improve the reliability and usability of the dataset for machine learning.

3. Collinearity Analysis and Feature Selection

The final stage focuses on identifying redundant features.

Tasks performed:

Correlation analysis
Collinearity visualization
Identification of highly correlated features
Recommendation of features to remove
Reducing collinearity improves model interpretability and performance.

# Key Insights

From the exploratory analysis, several important observations were identified:

Some variables contain missing values that require cleaning
Certain features exhibit strong correlations
A few features may introduce multicollinearity
Data transformations are required before model training
These insights guide the preparation of the dataset for predictive modeling.

# Technologies Used

Python libraries used in this project:

Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

The analysis is implemented using Python in a Jupyter Notebook.
