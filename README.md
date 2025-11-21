# Market-Risk-Time-Series-ML-Analytics-System
An end-to-end Market Risk Analytics platform combining time-series econometrics, machine learning forecasting, anomaly detection, and cloud-enabled deployment to support modern risk management workflows.


## Project Overview
Financial institutions need scalable systems to:
- Analyze and monitor market risk factors
- Forecast volatility and regime changes
- Detect abnormal price movements
- Standardize risk analytics into reusable Python libraries
- Deploy models and pipelines on cloud platforms
- Deliver rich risk dashboards for stakeholders

This project builds a complete solution addressing all these needs.


## Key Features
1. Econometric Time-Series Modeling
- ARIMA/SARIMA for returns prediction
- GARCH for volatility modeling
- Vector AutoRegression (VAR) for multi-factor interactions
- Cointegration & stationarity tests


2. Machine Learning & Anomaly Detection
- Gradient Boosted Trees for short-term forecasting
- LSTM deep-learning models
- Isolation Forest / One-Class SVM for anomaly flags
- Market-regime classification


3. Custom Python Analytics Library (OOP)
Reusable OOP-based library:

        risk_analytics_lib/
            econometrics/
            ml/
            anomalies/
            utils/
   
Includes:
- Data cleaning
- Feature engineering
- Time-series models
- Forecasting pipelines
- Backtesting utilities
- Visualization tools
- Explainability wrappers (SHAP)


4. Cloud Deployment (AWS/Snowflake)
- Data stored in S3/Snowflake
- Automated inference pipeline via AWS Lambda
- Model outputs written back to cloud storage
- Dashboard pulling live data from cloud


5. Interactive Market Risk Dashboard

    Built using Streamlit, featuring:
  - Volatility forecasts
  - Anomaly heatmaps
  - VaR driver trends
  - Market stress scenarios
  - Regime shift timelines


## Use Cases
- Market risk analytics & exposure monitoring
- Volatility prediction & stress signals
- Regime shift and anomaly detection
- Automated risk reporting
- Cloud-native risk ML systems
