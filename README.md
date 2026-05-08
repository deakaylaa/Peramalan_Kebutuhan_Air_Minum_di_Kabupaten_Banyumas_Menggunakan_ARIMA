# Water Demand Forecasting in Banyumas Regency using ARIMA

This project is a time series analysis to forecast clean water needs in Banyumas Regency, Central Java. I used the **ARIMA (Autoregressive Integrated Moving Average)** method to analyze data from 2016 to 2018 and predict future demand.

---

## Project Overview
* **Goal**: To analyze water consumption patterns and forecast future needs for better government planning.
* **Method**: ARIMA Modeling (Identification, Estimation, Diagnostic Testing, and Forecasting).
* **Dataset**: Monthly water distribution data in Banyumas Regency (Source: BPS Banyumas).
* **Tools**: R / Python (Time Series Libraries).

## Key Results
* **Best Model**: The analysis identified **ARIMA (0,1,2)** as the most accurate model based on the lowest AIC value (877.15).
* **Forecast**: The estimated total water demand for **January to May 2019** is **7,077,824 cubic meters**.
* **Accuracy**: The model showed a close fit between actual data and predicted values.

## Steps in this Project
1. **Stationarity Check**: Visualized data plots and performed differencing to make the data stationary.
2. **Model Identification**: Used ACF and PACF plots to find potential ARIMA parameters.
3. **Parameter Estimation**: Compared multiple models (ARIMA 2,1,0; 0,1,2; and 2,1,2) using Z-tests.
4. **Diagnostic Checking**: Checked residuals using Ljung-Box test and T-tests to ensure the model is valid.
5. **Forecasting**: Generated a 5-period ahead forecast for 2019.

## Skills Demonstrated
* Statistical Inference & Hypothesis Testing.
* Time Series Forecasting (ARIMA).
* Data Visualization & Interpretation.
* Predictive Analytics for Public Policy.

<img width="470" height="341" alt="image" src="https://github.com/user-attachments/assets/9ac9177a-9126-4f1b-8aaf-5a62ce3e3d49" />
