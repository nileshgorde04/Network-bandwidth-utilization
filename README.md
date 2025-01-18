# Network Bandwidth Utilization Prediction

## Project Overview

This project aims to predict and optimize network bandwidth utilization using machine learning techniques. The model is built to analyze bandwidth data, predict future utilization, and assist in efficient bandwidth management. It uses Long Short-Term Memory (LSTM) networks for time series prediction.

## Key Features

- **Data Preprocessing**: The project includes steps for data cleaning, normalization, and splitting the dataset into training and testing sets.
- **Model Building**: Utilizes LSTM (Long Short-Term Memory) networks for predicting future bandwidth utilization.
- **Evaluation Metrics**: The model's performance is evaluated using MAE (Mean Absolute Error), MSE (Mean Squared Error), and RMSE (Root Mean Squared Error).
- **Visualization**: Actual vs. predicted utilization are plotted for analysis.

## Requirements

To run this project, you'll need the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `keras`
- `tensorflow`

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib scikit-learn keras tensorflow
