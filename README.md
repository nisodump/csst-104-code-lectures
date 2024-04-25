# CSST-104: Advance Machine Learning Lectures
 This repository contains code-along on the lectures from CSST 104 - Advanced Machine Learning.

## Table of Contents
1. <a href="Simple-Linear-Regression/simple_linear_regression.html">Simple Linear Regression</a>
2. <a href="Multiple-Linear-Regression/multiple_linear_regression.html">Multiple Linear Regression</a>
3. <a href="Logistic-Regression/logistic_regression.html">Logistic Regression</a>
4. <a href="Time-Series-Analysis-Using-ARIMA-Model/time_series_analysis_using_arima.html">Time Series Analysis Using ARIMA Model</a>

## Lecture Overview
1. [Simple Linear Regression](https://www.scribbr.com/statistics/simple-linear-regression/) is a statistical technique used in programming, particularly in data analysis and machine learning, to model the relationship between a dependent variable (usually denoted as 𝑦) and one independent variable (usually denoted as 𝑥). The goal is to fit a linear equation to the data points that best describes the relationship between the variables.
2. [Multiple Linear Regression](https://www.scribbr.com/statistics/multiple-linear-regression/) is an extension of Simple Linear Regression where the relationship between a dependent variable (𝑦) and multiple independent variables (𝑥1, 𝑥2, …, 𝑥𝑛) is modeled using a linear equation. The goal is to estimate the coefficients for each independent variable that best fit the data and predict the dependent variable.
3. [Logistic Regression](https://www.ibm.com/topics/logistic-regression) is a statistical method used for binary classification tasks, where the goal is to predict the probability of an observation belonging to a particular class or category. Unlike linear regression, which predicts continuous numeric values, logistic regression predicts the probability of a binary outcome.
4. [Time Series Analysis using ARIMA ((AutoRegressive Integrated Moving Average)) Model](https://towardsdatascience.com/an-introduction-to-time-series-analysis-with-arima-a8b9c9a961fb) is a method used to analyze and forecast time series data. It is particularly useful for data that exhibits trends and seasonal patterns.
   - **AutoRegressive (AR) Component:**
     - The AR part of ARIMA models the relationship between an observation and a certain number of lagged observations (previous time steps). It captures the autoregressive behavior of the data, where current values depend on past values.
     - An AR(p) model includes the p most recent observations as predictors.
   - **Integrated (I) Component:**
     - The Integrated part of ARIMA indicates the number of times differencing is needed to make the time series stationary. Stationarity is important for time series analysis because it assumes that the statistical properties of the data do not change over time.
     - If the original time series is not stationary (i.e., it has trends or seasonality), differencing can be applied to remove these patterns.
   - **Moving Average (MA) Component:**
     - The MA part of ARIMA models the relationship between an observation and a residual error from a moving average model applied to lagged observations.
     - An MA(q) model includes the q most recent residual errors as predictors.
