# Wine Quality Prediction

## OIBSIP Internship

* **Track:** Data Analytics
* **Level/Task:** Level 2 - Task 2
* **Project:** Wine Quality Prediction

## Project Overview

This project builds and compares multiple **classification models** to predict wine quality using physicochemical properties such as acidity, density, alcohol content, sulphates, and pH. The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), class imbalance analysis, feature engineering, model training, evaluation, visualization, and feature importance interpretation.

## Objectives

* Perform initial data inspection
* Analyze descriptive statistics
* Explore the distribution of wine quality scores
* Analyze class imbalance in quality ratings
* Handle target transformation through binary classification
* Analyze feature correlations
* Train multiple classification models
* Evaluate model performance using accuracy and classification metrics
* Visualize confusion matrices
* Analyze feature importance using Random Forest
* Compare the performance of multiple classifiers
* Identify the most suitable model for deployment

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

**Wine Quality Dataset**

**Source:** UCI Machine Learning Repository

The dataset contains physicochemical measurements of red wine samples, including fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, sulphates, alcohol, density, pH, and quality ratings.

## Features Implemented

* Data Loading and Inspection
* Missing Value Analysis
* Descriptive Statistics
* Wine Quality Distribution Analysis
* Class Imbalance Discussion
* Binary Target Feature Engineering (Good/Bad Wine)
* Correlation Heatmap
* Train/Test Split with Stratification
* Random Forest Classifier Training
* SGD Classifier Training
* Support Vector Classifier (SVC) Training
* Model Evaluation (Accuracy, Classification Report, Confusion Matrix)
* Random Forest Feature Importance Visualization
* Model Performance Comparison Table

## Project Structure

DataAnalytics-Level2-Task2-WineQualityPrediction/
│
├── Data/
│   └── winequality-red.csv
│
├── Notebook/
│   └── Wine_Quality_Prediction.ipynb
│
├── Screenshots/
│
├── README.md
├── requirements.txt
└── .gitignore

## Key Insights

* **Alcohol content** has one of the strongest positive influences on wine quality.
* **Volatile acidity** negatively impacts wine quality.
* **Sulphates** contribute positively to predicting high-quality wine.
* The dataset is **imbalanced**, with quality scores 5 and 6 occurring most frequently.
* Converting wine quality into **binary classes (good/bad)** improves classification performance.

## Model Evaluation

Three classification models were evaluated:

* **Random Forest Classifier**
* **SGD Classifier**
* **Support Vector Classifier (SVC)**

Performance was assessed using:

* **Accuracy**
* **Classification Report (Precision, Recall, F1-score)**
* **Confusion Matrix**

A comparison table was created to evaluate the predictive performance of all three models.

## Business Recommendations

* Prioritize improving **alcohol balance and sulphate levels** to increase the likelihood of producing high-quality wine.
* Monitor **volatile acidity** carefully, as higher values are associated with lower quality ratings.
* Use **Random Forest** for production deployment due to its strong predictive performance and feature interpretability.
* Apply predictive modeling during quality control to identify potentially high-quality wines before market release.
* Consider techniques such as **class balancing or resampling** when building future multi-class quality prediction systems.

## Author

* **Name:** Suhana
* **Internship:** Oasis Infobyte (OIBSIP)
* **Track:** Data Analytics
