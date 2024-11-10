# Bike-Demand-Prediction-with-Machine-Learning

## Overview
Welcome to the **Predicting Bike-Sharing Demand** repository! This project applies **Gradient Boosting (GBM)** and **Random Forest** machine learning models to predict the daily and hourly demand for bikes in a bike-sharing system. By examining features such as weather conditions, season, day of the week, holidays, and hour of the day, this project provides insights into customer behavior trends, including both **registered and casual users**, helping optimize bike availability and meet user demand efficiently.

This project is designed to aid bike-sharing operators in making data-driven decisions for fleet management, ensuring better service for users based on predictive insights.

## Project Structure
- **GBM_BikeSharingDemand.ipynb**: Jupyter notebook implementing the Gradient Boosting Model (GBM) to predict bike-sharing demand with high accuracy.
- **RandomForest_BikeSharingAlgorithm.ipynb**: Jupyter notebook exploring a Random Forest model to predict demand and assess feature importance.
- **train.csv**: Dataset containing historical bike rental data, used for model training.
- **test.csv**: Dataset containing new data for evaluating model performance.

## Project Highlights
- **Feature Engineering**: Key features, including weather conditions, temperature, humidity, hour, and day, are engineered to enhance predictive accuracy.
- **Model Comparison**: Both GBM and Random Forest models are trained and compared based on metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- **Insights Generation**: Analysis of predicted demand patterns for registered and casual users under various conditions, allowing for targeted operational improvements in bike availability.

## Results/Summary
The models successfully predict bike-sharing demand with a high level of accuracy, providing actionable insights for bike-sharing system operators. Key findings include:

- **Weather Impact**: Weather conditions significantly affect demand, with higher temperatures and clear skies resulting in increased rentals.
- **Time-based Trends**: Demand peaks during rush hours on weekdays for registered users, while weekends see higher usage by casual users.
- **Feature Importance**: Model analysis reveals that features like hour of the day, temperature, and humidity are critical predictors of bike demand.

These insights enable bike-sharing services to proactively manage bike availability, anticipate demand surges, and optimize fleet distribution based on weather and time, enhancing overall user satisfaction and operational efficiency.

