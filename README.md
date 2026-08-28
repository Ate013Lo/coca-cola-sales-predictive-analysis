# Coca-Cola FEMSA | Sales Predictive Modeling

## Overview

This project develops a predictive modeling approach to analyze and forecast Coca-Cola FEMSA beverage sales, with the objective of supporting demand and production planning.

The analysis focuses on identifying the relationship between beverage sales and a set of economic, demographic, consumer, and environmental variables. The project applies econometric and machine learning techniques to evaluate which factors provide the strongest explanatory power for sales performance.

## Business Problem

Coca-Cola FEMSA needs to estimate beverage demand in order to support production planning and align supply with market demand.

The objective of this project is to develop and evaluate predictive models capable of estimating beverage sales based on historical data and relevant external factors.

The target variable is:

- `sales_unitboxes` — beverage sales measured in unit boxes

The explanatory variables considered include:

- Consumer sentiment
- GDP per capita
- CPI
- Inflation rate
- Unemployment rate
- Economic activity
- Economic activity growth
- Population density
- Job density
- Minimum wage
- Exchange rate
- Maximum temperature
- Holiday periods

## Methodology

The analysis follows a structured data analytics and predictive modeling workflow:

1. **Data Exploration**
   - Dataset structure and descriptive statistics
   - Data quality assessment
   - Missing-value analysis
   - Variable inspection

2. **Data Preparation**
   - Selection of numerical variables
   - Data transformation
   - Natural logarithmic transformations for selected variables
   - Preparation of features for statistical modeling

3. **Exploratory Data Analysis**
   - Statistical analysis
   - Correlation and relationship analysis
   - Visualization of explanatory variables against sales
   - Identification of potentially significant predictors

4. **Model Specification**
   - Definition of the dependent and independent variables
   - Hypothesis formulation
   - Train-test data split

5. **Predictive Modeling**
   - Multiple Linear Regression
   - Polynomial Regression
   - Lasso Regression
   - Ridge Regression
   - Ordinary Least Squares (OLS)

6. **Model Evaluation**
   - R²
   - Adjusted R²
   - AIC
   - BIC
   - F-statistic
   - Statistical significance
   - Predictive performance on test data

## Key Results

The multiple linear regression model using economic activity, maximum temperature, and population density achieved an **R² of 0.706**, indicating that the model explained approximately 70.6% of the observed variation in beverage sales within the analyzed sample.

A polynomial regression specification achieved an **R² of 0.837**, although its adjusted R² was lower (0.643), highlighting the importance of balancing model fit with model complexity. :contentReference[oaicite:1]{index=1}

These results demonstrate how combining econometric analysis with predictive modeling can provide insights into the factors associated with beverage demand.

## Technologies & Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Matplotlib
- Seaborn
- TensorFlow / Keras

## Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Statistical Analysis
- Econometric Modeling
- Feature Transformation
- Multiple Linear Regression
- Polynomial Regression
- Regularization (Lasso & Ridge)
- Model Evaluation
- Data Visualization
- Business-Oriented Predictive Analytics

## Project Structure

```text
├── Evidencia_Cocacola.ipynb
└── README.mdv
