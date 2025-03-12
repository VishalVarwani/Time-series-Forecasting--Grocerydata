Demand Forecasting using Machine Learning

Introduction

Demand forecasting is a crucial aspect of supply chain management, helping businesses optimize inventory, reduce waste, and meet customer demand efficiently. This project implements a time-series forecasting model using deep learning techniques to predict future demand based on historical data.

Features

Data loading and preprocessing

Time-series train-test splitting

Feature scaling using MinMaxScaler

Incorporates sales and weather features (temperature, precipitation, relative humidity, etc.)

Deep learning model for forecasting

Performance evaluation

Dataset

The dataset consists of historical grocery sales data aggregated over time. It includes various time-series features such as:

Sales Data: Transaction records from grocery stores

Weather Data: Temperature, precipitation, relative humidity, and other weather variables

These features are used to enhance demand forecasting accuracy by capturing external influencing factors
## Usage
1. Clone the repository:

2. Open the Jupyter Notebook and run all the cells:
 
3. Follow the structured sections to understand data preprocessing, model training, and evaluation.

## Model Details
- **Input**: Time-series demand data
- **Preprocessing**: Scaling and feature engineering
- **Model**: Deep learning (LSTM using PyTorch)
- **Output**: Predicted demand for future periods

## Results and Evaluation
The model is evaluated using standard metrics such as:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)



