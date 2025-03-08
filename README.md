# Data-Driven Product Management Conducting a Market Analysis

Power Consumption Prediction

Project Overview

This project aims to predict daily power consumption in a given area using machine learning models. The dataset contains features such as date, year, semester, day of the week, week in the year, day in the year, and month. Two machine learning models, Random Forest Regressor and XGBoost Regressor, are trained to make accurate predictions of power consumption.

How the Code Works

Data Preparation:

Loads the dataset containing power consumption records.

Selects relevant features for training.

Splits the data into training and testing sets.

Model Training and Hyperparameter Tuning:

Uses GridSearchCV to perform hyperparameter tuning on both models.

Selects the best-performing model based on Root Mean Squared Error (RMSE).

Performance Evaluation:

Computes RMSE for both models to assess accuracy.

Compares predicted vs. actual power consumption through a visualization.

Determines if the predictions follow the trend of actual values.

Results

The trained models provide accurate predictions for power consumption trends.

The model with the lowest RMSE is considered the best-performing model.

A correlation check determines if the predictions align well with actual trends.

Usage

To run the project:

Install necessary dependencies:

pip install pandas numpy matplotlib scikit-learn xgboost

Run the script:

python power_consumption_ml.py

View the plotted comparison and printed RMSE values.

Future Improvements

Experiment with additional features to enhance model accuracy.

Implement deep learning techniques for better performance.

Deploy the model as an API for real-time power consumption predictions.

Author

Developed by Warren Cheng.

License

This project is licensed under the MIT License.
