# House Price Prediction with Linear Regression

## OIBSIP Internship

**Track:** Data Analytics
**Level/Task:** Level 2 - Task 1
**Project:** Predicting House Prices with Linear Regression

## Project Overview

This project builds and evaluates a **Linear Regression model** to predict house prices using property features such as area, location, number of rooms, construction quality, garage capacity, and year built. The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature encoding, model training, evaluation, visualization, and coefficient interpretation.

## Objectives

* Perform initial data inspection
* Analyze descriptive statistics
* Explore the distribution of house prices
* Identify important predictive features
* Handle missing values
* Encode categorical variables using One-Hot Encoding
* Analyze feature correlations with house prices
* Train a Linear Regression model
* Evaluate the model using MSE, RMSE, and R² Score
* Visualize prediction performance and residuals
* Compare Linear Regression with Ridge Regression
* Generate business insights from model coefficients

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Visual Studio Code

## Dataset

**House Prices: Advanced Regression Techniques**
**Source:** Kaggle

The dataset contains residential property information such as neighborhood, lot area, overall quality, living area, garage details, and sale price.

## Features Implemented

* Data Loading and Inspection
* Missing Value Analysis
* Descriptive Statistics
* House Price Distribution Analysis
* Feature Selection Discussion
* One-Hot Encoding of Categorical Features
* Correlation Heatmap
* Train/Test Split (80/20)
* Linear Regression Model Training
* Model Evaluation (MSE, RMSE, R²)
* Actual vs Predicted Price Visualization
* Residual Plot Analysis
* Coefficient Analysis
* Ridge Regression Comparison

## Project Structure

DataAnalytics-L2-HousePricePrediction/
│
├── data/
│   └── train.csv
│
├── notebook/
│   └── House_Price_Prediction.ipynb
│
├── screenshots/
│
├── README.md
├── requirements.txt
└── .gitignore

## Key Insights

* **Overall Quality (OverallQual)** has the strongest positive impact on house prices.
* **Above-ground living area (GrLivArea)** significantly increases property value.
* **Garage capacity and total basement area** are important predictors of sale price.
* Location-based features (Neighborhood) contribute substantially to price differences.
* Ridge Regression provides slightly more stable predictions by reducing coefficient magnitude and overfitting.

## Model Evaluation

The model was evaluated using:

* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

A comparison between **Linear Regression** and **Ridge Regression** was performed to assess predictive performance and generalization capability.

## Business Recommendations

* Prioritize construction quality improvements to increase property value.
* Invest in increasing usable living space and garage capacity.
* Consider neighborhood-specific pricing strategies.
* Use predictive modeling to estimate property prices before listing.
* Apply regularized regression models when dealing with highly correlated housing features.

## Author

**Name:** Suhana

**Internship:** Oasis Infobyte (OIBSIP)

**Track:** Data Analytics
