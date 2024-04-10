# Climate TempTrend Hub

Time Series Analysis &amp; Forcasting Of Global Average Temperature 

<img src="https://github.com/Davidsonity/IBM-Help/assets/96771321/9afbf272-b0ff-48ba-8461-7d99d70c9d4e" alt="shutterstock_globalwarming" width="600">

This repository contains code and analysis for exploring the global average temperature anomaly relative to the 1961-1990 average temperature. The dataset provides insights into the deviations in temperature over time, offering valuable information for understanding climate trends and variability.

## Data Loading
The dataset was loaded using Python's pandas library to facilitate data manipulation and analysis. Necessary libraries including pandas, numpy, matplotlib, statsmodels, and plotly were imported.

## Data Preparation
Unnecessary columns were dropped to focus on relevant data for analysis. The dataset was then renamed for clarity.

## Time Series Analysis
The 'Year' column was converted to datetime format, and the data was grouped by year for time series analysis. Insights were derived from plotting the temperature anomalies over time, revealing trends, variability, and recent extremes.

## Additive Seasonal Decomposition
Seasonal decomposition was performed to separate the data into trend, seasonal, and residual components, providing further insights into the underlying patterns.

## Data Splitting: Training and Testing Sets
The data was split into training and testing sets to evaluate the performance of forecasting models.

## Autoregressive Integrated Moving Average (ARIMA) Model Implementation
The ARIMA model was implemented to forecast temperature anomalies. Order determination was performed using ACF and PACF plots, and the model was evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Exponential Smoothing (ETS)
Exponential Smoothing was applied as an alternative forecasting method, and its performance was evaluated using MAE and RMSE.

## Prophet
The Prophet model was employed for forecasting with seasonality disabled. Its performance was assessed using MAE and RMSE.

## Gradient Boosting Regressor (GBR)
A Gradient Boosting Regressor model was utilized for temperature anomaly forecasting, and its performance was evaluated using MAE and RMSE.

## Long Short-Term Memory (LSTM)
An LSTM model was implemented for temperature anomaly forecasting, leveraging its ability to capture long-term dependencies in time series data. The model's performance was evaluated using MAE and RMSE.

## Comparing Models Performance
The performance of each forecasting model was compared based on MAE and RMSE, highlighting the strengths of the LSTM model in capturing the complexities of the dataset.

## Insights from Comparison
The LSTM model demonstrated superior performance compared to traditional time series forecasting methods, indicating its effectiveness in capturing the underlying patterns in temperature anomaly data.

## Forcasting with Best Model (LSTM)
| Year       | Temperature |
|------------|-------------|
| 2025-12-31 | 1.068672    |
| 2026-12-31 | 1.111708    |
| 2027-12-31 | 1.198443    |
| 2028-12-31 | 1.291146    |
| 2029-12-31 | 1.336305    |
| 2030-12-31 | 1.384188    |

This repository provides a comprehensive analysis and Forcasting of global average temperature anomalies and serves as a valuable resource for understanding climate trends and variability.
