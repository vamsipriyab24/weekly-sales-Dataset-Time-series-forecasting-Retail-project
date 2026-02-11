# weekly-sales-Dataset-Time-series-forecasting-Retail-project
This project focuses on forecasting weekly sales by leveraging statistical analysis and machine learning. The goal was to move from baseline regression models to sophisticated time-series architectures capable of capturing complex seasonality and trend patterns.

Methodology & Technical Workflow
Exploratory Data Analysis (EDA) & Statistical Testing Before modeling, I performed rigorous data validation to ensure the integrity of the forecast:Decomposition: Performed seasonal decomposition to isolate Trend, Seasonality, and Residuals.Stationarity Testing: Utilized the Augmented Dickey-Fuller (ADF) test to check for stationarity, followed by differencing to stabilize the mean.
Correlation Analysis: 
Analyzed ACF (Autocorrelation Function) and PACF (Partial Autocorrelation Function) plots to determine the optimal $p, d, q$ 
parameters for statistical modeling
Model Evolution implemented a multi-stage modeling approach to compare traditional ML against statistical time-series models:
Baseline: Started with Logistic Regression (classification of sales targets) and Random Forest Regressor to capture non-linear relationships and feature importance.Advanced Forecasting: Developed a SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous variables) model. This allowed for the integration of external factors (e.g., holidays, promotions) while handling the 52-week seasonality inherent in retail data.
Performance Metrics
Models were evaluated using Mean Absolute Percentage Error (MAPE) and RMSE, ensuring the final SARIMAX model provided the highest reliability for business planning.
Key Technical Stack Language: Python (Jupyter Notebook)
Libraries: Pandas, NumPy, Statsmodels (ADF, SARIMAX), Scikit-learn, Matplotlib/Seaborn

