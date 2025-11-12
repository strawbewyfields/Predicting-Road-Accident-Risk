# Predicting-Road-Accident-Risk
Predict the likelihood of accidents on different types of roads

## Project Overview
This project is part of the Kaggle Playground Competition. The goal is to predict the likelihood of road accidents (a continuous target between 0 and 1) using a synthetically generated dataset. The dataset was created using a deep learning model trained on the original Simulated Roads Accident dataset, with feature distributions closely resembling—but not identical to—the original data. Submissions are evaluated using Root Mean Squared Error (RMSE) between predicted and actual accident_risk values

## Objective
Build a machine learning model to predict accident_risk based on various road and environmental features

## Dataset Details
- train.csv: Contains the training data with the target variable accident_risk.
- test.csv: Contains the test data for which predictions must be submitted.
- Features include: road type, curvature, speed limit, lighting conditions, weather, time of day, and more

## Key Findings
- Initial exploration highlighted factors like road curvature and lighting conditions as potentially influential on accident risk, a finding later supported by model analysis.
- Our model identified road curvature (approx. 36%) and lighting conditions (approx. 25%) as the most important features for predicting accident risk.
- Weather conditions also showed some contribution (approx. 7%).
## Model Performance (Random Forest Regressor)
- Achieved a cross-validation RMSE of approximately 0.057.
- Observed a small gap between training and validation RMSE (around 0.0052), suggesting the model is reasonably balanced (not severely over/underfitting) on this dataset.
