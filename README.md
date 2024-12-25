# Final-project-SCA
 
  
  # **India Rental House Predict**
![image](https://github.com/user-attachments/assets/832121de-8315-4e4d-a1f0-30a8974e21bb)


# Indian Rental House Price Prediction

## Overview
This project aims to predict rental house prices in India using various machine learning models. The goal is to develop accurate models that help landlords and tenants make informed decisions about rental prices.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Collection and Preparation](#data-collection-and-preparation)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Feature Engineering](#feature-engineering)
5. [Model Building](#model-building)
6. [Model Evaluation](#model-evaluation)
7. [Results](#results)
8. [Conclusion](#conclusion)
9. [Future Work](#future-work)
10. [Acknowledgments](#acknowledgments)

## Introduction
Predicting rental house prices in India using machine learning models. The project involves data cleaning, feature engineering, model building, and evaluation to identify the best-performing model for accurate predictions.

## Data Collection and Preparation
### Data Sources
The data was collected from various sources, including public housing datasets and real estate websites.

### Data Cleaning
- Dropped irrelevant columns
- Split and transformed columns like `house_type` and `house_size`
- Handled missing values

## Exploratory Data Analysis (EDA)
### Summary Statistics
- Provided insights into the distribution of key features such as price, house size, and number of rooms.

### Visualizations
- Created histograms to visualize the distribution of rental prices.
  ![image](https://github.com/user-attachments/assets/3e7269fa-89c3-465f-8a1f-3378119febb9)

- Plotted correlation heatmaps to identify relationships between features.
![image](https://github.com/user-attachments/assets/22f836bf-d65d-4689-aaac-fb312b5c6260)

## Feature Engineering
- Created new features such as `distance_to_center` to add more predictive power to the models.
- Encoded categorical features using one-hot encoding.

## Model Building
### Models Used
- **Linear Regression:** Simple linear model to establish a baseline.
- **Random Forest:** Ensemble model to capture complex interactions between features.
- **XGBoost:** Advanced boosting algorithm for high accuracy.

## Model Evaluation
### Performance Metrics
- **Mean Squared Error (MSE):** Measures the average of the squares of the errors.
- **R-squared (R²):** Indicates the proportion of the variance in the dependent variable predictable from the independent variables.
- **Out-of-Bag (OOB) Score:** Used for Random Forest.

### Comparison
- Evaluated model performance using the metrics mentioned above.
- Identified the best-performing model based on R-squared and MSE.

## Results
- The Random Forest model had the highest R-squared value and the lowest MSE, and high oob-score  making it the most accurate model for predicting rental prices.
- Feature importance analysis revealed key factors influencing rental prices, such as house size, number of bathrooms, and location.

![image](https://github.com/user-attachments/assets/0bc014ad-8768-4e72-b1ec-dd843744ae27)

## Conclusion
- Developed models to predict rental house prices in India accurately.
- Identified key factors influencing rental prices.
- The XGBoost model was found to be the best-performing model.

## Future Work
- Further refine the models by tuning hyperparameters.
- Explore additional data sources for more comprehensive predictions.
- Implement more advanced feature engineering techniques.

## Acknowledgments
- Thanks to mentors, contributors, and supporting organizations for their guidance and support.


