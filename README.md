# Grain Humidity Prediction using Machine Learning
## Overview
This project aims to predict grain humidity based on various environmental factors such as temperature, moisture levels, and other relevant parameters. The dataset used in this project contains time-series data with multiple features, including temperature readings (heated, outdoor, low, high) and moisture levels from different sensors. The goal is to build a machine learning model that can accurately predict grain humidity, which is crucial for optimizing storage conditions and preventing spoilage.

## Dataset
The dataset includes the following features:

temp_heated: Temperature of the heated grain.
temp_out: Outdoor temperature.
temp_low: Low temperature reading.
temp_high: High temperature reading.
moist_F: Moisture level from sensor F.
moist_V: Moisture level from sensor V.
moist_E: Moisture level from sensor E.
moist_true: True moisture level (target variable).
The data is collected over time, with timestamps indicating when each reading was taken.

## Methodology
### Data Preprocessing:

Handle missing values and normalize the data.
Split the dataset into training and testing sets.
Perform exploratory data analysis (EDA) to understand the relationships between features.

### Feature Engineering:

Create new features that might help in predicting grain humidity.
Use techniques like rolling averages or differences to capture temporal patterns.

### Model Selection:

Experiment with different machine learning models such as Linear Regression, Random Forest, Gradient Boosting, and Neural Networks.
Use cross-validation to evaluate model performance.

### Model Training:

Train the selected models on the training dataset.
Tune hyperparameters using grid search or random search.

### Model Evaluation:

Evaluate the models on the test dataset using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
Compare the performance of different models.

### Visualization:

Plot the actual vs predicted values to visually assess the model's performance.
Create visualizations to show the importance of different features.

### Results
The best-performing model achieved an as results ensemble models were:
Dataset 1: MSE = 1.7972, MAPE = 6.32%
Dataset 2: MSE = 1.6533, MAPE = 5.02%
Dataset 4: MSE = 1.6967, MAPE = 5.74%
