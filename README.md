# UJatim - Shrimp Price Time Series Modeling

## Project Overview

The **UJatim** project focuses on modeling and forecasting shrimp prices in **East Java**, Indonesia, using time series data. Shrimp prices play a vital role in the region’s economy, and understanding their trends is crucial for stakeholders in the shrimp industry, including farmers, traders, and policymakers.

As the **Data Scientist** on this project, I successfully developed two distinct time series models to predict shrimp prices for datasets with **60** and **100** data points, respectively. These models are designed to provide accurate forecasts, helping to anticipate price movements and optimize decision-making.

## Project Objectives

The main objectives of this project were to:
- Analyze and preprocess shrimp price data from East Java.
- Develop and evaluate time series models for price forecasting.
- Provide insights and recommendations based on the model results.

## Data

The dataset consists of shrimp prices collected over time from various regions in **East Java**, Indonesia. The data was used to build two different models, focusing on datasets with:
- **60 data points** (for short-term forecasting)
- **100 data points** (for longer-term forecasting)

## Time Series Models

I developed two key time series models:

1. **Model for Dataset with 60 Data Points**:
   - Focus: Short-term price forecasting.
   - Approach: The model was designed to capture recent price fluctuations and provide near-term predictions.
   - Techniques used: In this project, two models were initially created using different forecasting algorithms: SARIMA and ARIMA. The model with the best evaluation was selected for deployment.

2. **Model for Dataset with 100 Data Points**:
   - Focus: Longer-term price trends and forecasting.
   - Approach: This model aims to capture broader patterns over a larger dataset.
   - Techniques used: In this project, two models were initially created using different forecasting algorithms, SARIMA and ARIMA. The model with the best evaluation was selected for deployment.

## Methodology

The workflow followed for both models involved the following key steps:
1. **Data Preprocessing**: Cleaning and preparing the data, handling missing values, outliers, and ensuring time-based consistency.
2. **Exploratory Data Analysis (EDA)**: Understanding the trends, seasonality, and overall behaviour of the shrimp price data.
3. **Model Building**: Developing time series models tailored to each dataset's size.
4. **Model Evaluation**: Assessing the model's accuracy and performance using metrics such as MAE, RMSE, and MAPE.
5. **Forecasting**: Generating predictions for shrimp prices in East Java based on the best-performing models.

## Results

Both models delivered promising results for their respective data sizes:
- **60 Data Points Model**: Successfully captured short-term trends and provided accurate price forecasts for upcoming periods.
- **100 Data Points Model**: Accurately modelled long-term price trends, offering valuable insights into broader shrimp price movements.

## Future Work

- Extend the models to incorporate external factors (e.g., weather data, market demand) to improve forecasting accuracy.
- Explore other advanced time series techniques such as Prophet, LSTM, or seasonal decomposition methods.
- Automate the model updating process to ensure up-to-date forecasts as new data becomes available.

## Conclusion

This project successfully demonstrated the ability to model shrimp price data in East Java using time series techniques. The models were developed to provide actionable insights and predictions that stakeholders can use for better decision-making and market planning.

## Technologies Used

- Python
- Pandas
- Numpy
- Matplotlib
- Scikit-learn
- Statsmodels (or any other relevant library)
