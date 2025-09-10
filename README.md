# 📈 Time Series Forecasting - Monthly GDP of Brazil

[![R](https://img.shields.io/badge/R-4.x-blue.svg)](https://www.r-project.org/)
[![Time Series](https://img.shields.io/badge/Analysis-Time%20Series-green.svg)](https://img.shields.io)
[![Forecasting](https://img.shields.io/badge/Modeling-Forecasting-yellow.svg)](https://img.shields.io)
[![Economics](https://img.shields.io/badge/Field-Economic%20Analysis-red.svg)](https://img.shields.io)
[![UNICAMP](https://img.shields.io/badge/Institution-UNICAMP-orange.svg)](https://www.unicamp.br/)

This repository contains two analytical projects (**Project 1** and **Project 2**) developed for the course **CE442 – Economic Analysis Methods IV** at **State University of Campinas (UNICAMP)**. The projects involve a comprehensive time series analysis of Brazil's monthly **Gross Domestic Product (GDP)**, implementing various statistical and econometric techniques using **R**.

---

## 📋 Course Syllabus

1. **Time Series Decomposition Methods**  
2. **Exponential Smoothing Methods**  
3. **Holt and Holt-Winters Models**  
4. **Introduction to Time Series Transformations, Autocorrelation and Partial Autocorrelation Functions**  
5. **Stationary Stochastic Processes: ARMA Models**  
6. **Non-Stationary Stochastic Processes: Unit Root Tests and ARIMA Models**  
7. **Time Series Forecasting Analysis**

---

## 🔍 Project Overview

### Project 1: Classical Decomposition and Exponential Smoothing
- Visualization of monthly GDP time series (2010–2024)
- Seasonal adjustment using dummy variables and moving averages
- Classical decomposition: trend, seasonality, and irregular components
- Exponential smoothing models: Simple, Holt, and Holt-Winters
- Forecasts for 2023–2024 and error metrics (RMSE, MAE, MAPE)

### Project 2: ARIMA Modeling and Forecasting
- Seasonality identification and unit root testing (ADF)
- ARIMA modeling: identification, estimation, and diagnostic checking
- Residual analysis: autocorrelation, normality, and heteroscedasticity
- One-step-ahead and 24-step-ahead forecasts
- Model re-estimation using full dataset and 2025 forecasts

---

## 🛠️ Technologies Used

- **R Programming**
- Key Packages:
  - `forecast` - Time series forecasting
  - `lmtest` - Statistical tests
  - `tseries` - Time series analysis
  - `urca` - Unit root tests
  - `TTR` - Technical trading rules
  - `finTS` - Financial time series
  - `dplyr` - Data manipulation

---

## 📊 Key Results

- **Best Model**: ARIMA(4,1,4) selected based on AIC and BIC criteria
- **Accuracy Metrics**: RMSE, MAE, and MAPE for in-sample and out-of-sample forecasts
- **Residual Diagnostics**: Ljung-Box, Jarque-Bera, and ARCH tests
- **2025 Forecasts**: Point forecasts with 95% confidence intervals

## 🔗 Related Badges

[![RStudio](https://img.shields.io/badge/IDE-RStudio-75AADB.svg)](https://posit.co/)
[![Data Analysis](https://img.shields.io/badge/Application-Economic%20Policy-FF6B6B.svg)](https://img.shields.io)
[![Metrics](https://img.shields.io/badge/Validation-RMSE%20%7C%20MAE%20%7C%20MAPE-9B59B6.svg)](https://img.shields.io)
[![Stats](https://img.shields.io/badge/Statistics-Time%20Series%20Analysis-3498DB.svg)](https://img.shields.io)
