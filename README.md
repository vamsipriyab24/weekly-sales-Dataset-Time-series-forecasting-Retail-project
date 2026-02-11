# weekly-sales-Dataset-Time-series-forecasting-Retail Supply Chain problem-project
This project focuses on forecasting weekly sales by leveraging statistical analysis and machine learning. The goal was to move from baseline regression models to sophisticated time-series architectures capable of capturing complex seasonality and trend patterns.
# 📈 Weekly Sales Forecasting: Time-Series Analysis & Predictive Modeling

## 📌 Project Overview
This repository contains a comprehensive end-to-end data science workflow for forecasting weekly sales. The project transitions from baseline machine learning models to advanced statistical time-series architectures to capture complex seasonality and trends.

## 🛠️ Technical Stack
* **Language:** Python 3.x
* **Analysis:** Pandas, NumPy, Matplotlib, Seaborn
* **Statistical Testing:** Statsmodels (ADF, PACF/ACF)
* **Machine Learning:** Scikit-learn (Random Forest, Logistic Regression)
* **Time-Series Modeling:** SARIMAX

## 🚀 Workflow & Methodology

### 1. Statistical Pre-processing
Before modeling, I validated the data's structural integrity:
* **Stationarity:** Conducted the **Augmented Dickey-Fuller (ADF)** test.
* **Decomposition:** Isolated **Trend, Seasonality, and Residuals** to understand underlying patterns.
* **Correlation:** Used **ACF & PACF** plots to determine the $p, d, q$ and seasonal $P, D, Q$ parameters.

### 2. Modeling Approach
I evaluated multiple models to find the optimal balance between bias and variance:
* **Machine Learning Baselines:** Implemented **Logistic Regression** and **Random Forest** to establish a performance floor.
* **SARIMAX:** Developed a Seasonal AutoRegressive Integrated Moving Average model with Exogenous variables. This was chosen to handle the 52-week seasonality and potential external business drivers.

### 3. Evaluation
* **Metrics:** Focused on **MAPE (Mean Absolute Percentage Error)** and **RMSE**.
* **Validation:** Performed "Walk-forward" validation to ensure the model's reliability in a real-world production environment.



