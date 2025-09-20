# Air-Quality-Index-AQI-Analysis-Forecasting-Indian-Cities
Air Quality Index (AQI) analysis and forecasting for major Indian cities using time series models (Prophet &amp; SARIMAX). Includes data cleaning, EDA, visualizations, and future pollution level predictions with policy insights.
Air Quality Index (AQI) Analysis & Forecasting – Indian Cities
📌 Overview

This project analyzes historical air quality data from major Indian cities (Delhi, Mumbai, Kolkata, Bengaluru) and builds forecasting models to predict future pollution levels. The goal is to uncover trends in pollutants (PM2.5, PM10, NO2, SO2, etc.) and provide actionable insights for policymakers.

📂 Dataset

Source: CPCB
 & Kaggle – Air Quality Data in India (2015–2020)

Data includes multi-year AQI records across multiple monitoring stations.

Processed into daily averages for consistency.

🔎 Key Work Done

Cleaned and preprocessed raw AQI data (handled missing/inconsistent values).

Exploratory Data Analysis (EDA): pollutant distributions, seasonal trends.

Visualizations: time-series plots, monthly boxplots, interactive charts.

Applied Time Series Forecasting using:

Facebook Prophet – to capture seasonality and holiday effects.

SARIMAX – for autoregressive short-term forecasting.

Compared models to evaluate performance.

Identified high-risk zones and peak pollution periods.

📊 Results & Insights

Delhi has the worst AQI, with hazardous levels in winter months.

Mumbai shows moderate but frequent spikes due to traffic & weather.

Kolkata has strong festival-season peaks (Diwali, Durga Puja).

Bengaluru remains better but shows a rising trend.

Forecasts for the next 6–12 months highlight winter peaks and seasonal risks.

🛠 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Facebook Prophet, Statsmodels (SARIMAX)

Scikit-learn (for metrics)

This study highlights the severe and recurring air pollution challenges faced by major Indian cities, especially Delhi and Kolkata during winter months. Time series forecasting using Prophet and SARIMAX models successfully captured seasonal pollution trends, enabling short- and mid-term predictions. The insights generated can support policymakers in implementing targeted interventions to reduce emissions, protect public health, and promote sustainable urban growth.
Identified high-risk periods → mainly winter months in north India.

Produced a data-driven roadmap for policymakers with specific recommendations.
