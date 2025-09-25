# Trade-Volume-Stock-Volatility-Prediction
## 01 Introduction

This project, developed as part of BA870(Financial Analytics), focuses on building a predictive model to analyze trade volume, stock volatility, and post-earnings log returns. The goal is to better understand how financial and market indicators influence short-term stock behavior and provide insights into market trends and trading strategies.

## 02 Dataset

Source: Publicly available financial and stock market data (e.g., Yahoo Finance, WRDS, Alpha Vantage, etc.)

Features:

Daily trade volume

Stock returns (post-earnings)

Volatility measures

Market and financial indicators

Timeframe: Covers multiple earnings periods for robust analysis

## 03 Methods

Data Preprocessing

Cleaning missing and noisy values

Normalization and scaling

Feature selection and dimensionality reduction

Feature Engineering

Lagged variables for returns and volume

Rolling averages and moving volatility windows

Earnings event dummy variables

Modeling

Regression models (Linear, Lasso, Ridge)

Time-series models for volatility forecasting

Model evaluation using RMSE, R², and error metrics

## 04 Streamlit App

A Streamlit web app was developed to make the results interactive and user-friendly.

View past 7-day stock price trends

Explore daily trading volume

Forecast trade volume and volatility

Interactive visualizations for model outputs

## 05 Results & Insights

Identified patterns between post-earnings events and abnormal trading volume

Demonstrated predictive power of engineered features

Highlighted volatility spikes and their correlation with earnings announcements

## 06 How to Run

Clone this repository:

git clone https://github.com/your-username/Trade-Volume-Stock-Volatility-Prediction.git
cd Trade-Volume-Stock-Volatility-Prediction


Install dependencies:

pip install -r requirements.txt


Launch the Streamlit app:

streamlit run app.py

## 07 Contributors
Developed by Shuomeng Guan, Dizhao Zhang, Yixi Yu for BA870 course project. 
