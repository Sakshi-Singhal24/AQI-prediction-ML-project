# AQI Prediction using Machine Learning

## Overview
This project aims to predict the Air Quality Index (AQI) using air pollution data collected from various Indian cities. The project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, categorical encoding, feature scaling, and regression modeling.

## Problem Statement
Air quality is influenced by several pollutants such as PM2.5, PM10, NO2, NOx, SO2, and CO. The objective of this project is to analyze the relationship between these pollutants and AQI and build a machine learning model capable of predicting AQI values.

## Dataset
The dataset contains city-wise air quality measurements across India.

### Features Used
- PM2.5
- PM10
- NO2
- NOx
- SO2
- CO
- City
- Date

### Target Variable
- AQI (Air Quality Index)

## Project Workflow

### 1. Data Understanding
- Dataset inspection
- Statistical summary
- Data type analysis
- Missing value identification
- Duplicate value detection

### 2. Exploratory Data Analysis (EDA)
- AQI distribution analysis
- Outlier detection using boxplots
- Correlation analysis
- Pollutant vs AQI relationship analysis
- City-wise data distribution

### 3. Data Preprocessing
- Missing value treatment
- Feature selection
- Handling categorical variables
- Date feature transformation

### 4. Feature Engineering
- Extraction of temporal features from date data
- One-Hot Encoding for city information
- Feature scaling

### 5. Model Development
- Train-test split
- Multiple Linear Regression
- Model training and prediction

### 6. Model Evaluation
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Key Learnings
- Working with real-world datasets containing missing values and outliers
- Performing exploratory data analysis to derive meaningful insights
- Applying feature engineering techniques
- Building and evaluating regression models
- Understanding the impact of different pollutants on air quality

## Future Improvements
- Compare Linear Regression with advanced regression models
- Experiment with different imputation techniques
- Hyperparameter tuning
- Build an interactive AQI prediction dashboard
- Deploy the model as a web application

## Author
Sakshi Singhal
