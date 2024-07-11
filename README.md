
# Energy Consumption Forecasting Using Machine Learning Models
## Introduction
Energy consumption forecasting is crucial for energy management, policy-making, and operational efficiency. This project aims to develop various machine learning models to predict energy consumption based on historical data. By comparing different models, we aim to identify the most accurate and efficient model for forecasting.
## Objectives
•	To preprocess and analyze historical energy consumption data.
•	To develop and compare different regression models for predicting future energy consumption.
•	To evaluate the performance of each model using Mean Squared Error (MSE).
•	To visualize the actual vs. predicted values for better interpretability.
## Data Description
The data used in this project consists of historical energy consumption values measured in exajoules. The dataset is preprocessed to handle missing values and scale the data for better model performance.
Methodology
## Data Preprocessing
### 1.	Handling Missing Values:
Missing values in the 'Consumation' column are filled with the mean value of the column.
### 2.	Data Scaling:
The 'Consumation' data is scaled using MinMaxScaler to normalize the values between 0 and 1.
## Model Development
We develop and compare the following models:
### 1.	Linear Regression:
A basic linear approach to model the relationship between the dependent and independent variables.
### 2.	Decision Tree Regressor:
A tree-based model that splits the data into subsets based on feature values to make predictions.
### 3.	Random Forest Regressor:
An ensemble learning method that combines multiple decision trees to improve predictive performance.
### 4.	Support Vector Regressor (SVR):
A regression model that uses support vector machines to predict continuous values.
### 5.	k-Nearest Neighbors Regressor (k-NN):
A non-parametric method that predicts the target based on the k-nearest neighbors in the feature space.
### 6.	Long Short-Term Memory (LSTM) Network:
A type of recurrent neural network (RNN) that is capable of learning long-term dependencies and is particularly suited for time series prediction.
## Evaluation Metrics
The performance of each model is evaluated using Mean Squared Error (MSE), which measures the average squared difference between the actual and predicted values.

## Conclusion
This project demonstrates the application of various machine learning models to predict energy consumption. The comparison of different models helps identify the most accurate model for forecasting. The LSTM model, due to its ability to capture long-term dependencies, is expected to perform better in time series predictions.
