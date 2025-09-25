# Trade-Volume-Stock-Volatility-Prediction
## 01 Business Goal

There has always been a hype around using ML to predict stock prices. Yet this project, developed as part of Financial Analytics class at BU, focuses on building deep learning models to analyze **trade volume, stock volatility, and post-earnings log returns**. The reason being that the "alpha" (the extra return an investor earns above the market benchmark) is always sinking as today's markets are becoming more and more efficient. In other words, opportunities to consistently beat the market shrink. So instead of blindly following the majority, our goal is to create a tool that can really help interested individuals to better understand how financial and market indicators drive short-term stock behavior. By doing so, we aim to provide actionable insights into market trends and trading strategies, offering value where traditional price prediction falls short.

## 02 Dataset
There are four different types of data as input features to the predictive models
* Company related (e.g., has_devidend, has_acquisition, ROE, etc.)
* Financial news (sentiment score, average news count in different types of news)
* Macroeconomic factors (e.g., GDP, CPI, Unemployment rate, etc.)
* Technical factors (e.g., log_return, average of trading volume, momentum)

## 03 Methodology

* Data Preprocessing
  * Cleaning missing and noisy values
  * Normalization and scaling
* Feature selection and dimensionality reduction
* Feature Engineering
  * Lagged variables for returns and volume
  * Rolling averages and moving volatility windows
  * Earnings event dummy variables
* Modeling
  * Regression models (Linear, Lasso, Ridge)
  * Time-series models for volatility forecasting
* Model evaluation using RMSE, R², and error metrics

## 04 Streamlit App

A Streamlit web app was developed to make the results interactive and user-friendly with the following functions:
* View past 7-day stock price trends
* Explore daily trading volumeForecast trade volume and volatility
* Interactive visualizations (line graphs) for model outputs
*Unfortunately the app demo is currently unavailable as there are some issues with the backend of Yahoo Finance API*

## 05 Results & Insights

Some insightful patterns are identified. For example, high volume today could be predictive of higher volatility tomorrow; abnormal volume tends to cluster around earnings announcements, but the volatility response differs depending on whether the earnings beat or missed expectations.

## 06 How to Run

a. Clone this repository:
git clone https://github.com/eveningeve/Trade-Volume-Stock-Volatility-Prediction.git

cd Trade-Volume-Stock-Volatility-Prediction


b. Install dependencies:

pip install -r requirements.txt


c. Launch the Streamlit app:

streamlit run app.py

## 07 Contributors
Developed by Shuomeng Guan, Dizhao Zhang, Yixi Yu 
