

# Hotel Booking Cancellation Prediction

## Overview

This project focuses on predicting hotel booking cancellations using machine learning techniques. The goal is to identify influential factors, build a predictive model for advance cancellation prediction, and formulate profitable policies for cancellations and refunds.

## Business Objectives

1. Identify key factors influencing hotel booking cancellations.
2. Develop a predictive model for advance cancellation prediction.
3. Formulate profitable policies for cancellations and refunds to optimize revenue.

## Data

The dataset used in this project can be downloaded [here](https://raw.githubusercontent.com/vkoul/data/main/misc/hotel_bookings.csv).

## Data Processing and Exploration

- Imported relevant modules and libraries for data manipulation, visualization, and modeling.
- Loaded the dataset and performed initial data inspection.
- Parsed date columns properly and generated booking dates.
- Conducted univariate and bivariate analysis to understand the cancellation rate and relationships between different features.

## Data Preparation for Modeling

- Cleaned data by dropping duplicate rows and rows with zero prices.
- Engineered new features such as day, week, month, year, month name, and day name.
- Conducted further investigation to understand the correlation between features.
- Scaled numerical features for modeling.

## Model Building

### Logistic Regression

- Utilized Logistic Regression to build a predictive model.
- Achieved an accuracy score of {0.79} on the training data and {0.79} on the test data.

### K-Nearest Neighbors (KNN)

- Implemented the K-Nearest Neighbors model.
- Attained an accuracy score of {0.86} on the training data and {0.80} on the test data.

### Decision Trees

- Employed a Decision Trees model.
- Obtained an accuracy score of {0.99} on the training data and {0.85} on the test data.
- Explored feature importance and visualized the decision tree.

### Model Evaluation

- Utilized cross-validation to assess the generalization performance of each model.
- Cross-validation scores: Logistic Regression - {0.78%}, KNN - {0.79%}, Decision Trees - {0.84%}.

## Conclusion

This project provides insights into factors influencing hotel booking cancellations and delivers predictive models for advanced cancellation prediction. The models can assist in formulating profitable policies for cancellations and refunds to optimize revenue.

