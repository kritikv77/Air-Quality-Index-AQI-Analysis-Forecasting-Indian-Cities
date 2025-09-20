# Air-Quality-Index-AQI-Analysis-Forecasting-Indian-Cities
Air Quality Index (AQI) analysis and forecasting for major Indian cities using time series models (Prophet &amp; SARIMAX). Includes data cleaning, EDA, visualizations, and future pollution level predictions with policy insights.
📊 Air Quality Index (AQI) Analysis & Forecasting – Outputs Summary
1. Data Overview

Historical AQI and pollutant data was successfully cleaned and resampled to daily averages for major Indian cities: Delhi, Mumbai, Kolkata, and Bengaluru.

Missing values were filled using forward/backward filling and pollutant medians to maintain continuity.

The dataset spans multiple years with seasonal and festival-related variations.

2. Exploratory Data Analysis (EDA)

Time Series Plots show that:

Delhi consistently has the highest PM2.5 levels, with visible winter peaks (Nov–Jan) due to stubble burning, low wind speed, and festive emissions.

Mumbai shows moderate pollution, spiking occasionally during traffic congestion periods and local weather effects.

Kolkata has seasonal fluctuations, especially during festive seasons (e.g., Diwali, Durga Puja).

Bengaluru has relatively lower pollution but increasing urban growth shows gradual upward trends.

Monthly Boxplots revealed:

Clear seasonal patterns — winter months (Nov–Jan) show the worst AQI/PM2.5 values across all cities.

Summer (Apr–Jun) tends to have lower pollution due to better dispersion and rainfall.

3. Forecasting Results
🔮 Prophet Model

For each city, Prophet captured strong yearly and weekly seasonality:

Forecast shows continued high PM2.5 levels in winters, peaking in December/January.

Short-term forecasts (next 90 days) align with past seasonal trends.

Model performance:

Delhi: MAE ≈ 25–35 µg/m³, RMSE slightly higher due to extreme spikes.

Mumbai & Bengaluru: Lower MAE (≈ 10–20 µg/m³).

Kolkata: Moderate errors, seasonal spikes harder to capture.

🔄 SARIMAX Model (example)

Tested on one city (e.g., Delhi).

Gave a slightly better fit in terms of short-term prediction but struggled with long seasonal patterns compared to Prophet.

Best SARIMAX order found was around (1,1,1) or (2,1,1).

4. Key Findings

Delhi → Pollution crisis persists, with hazardous winter AQI. Policy must focus on stubble burning control + traffic management.

Mumbai → Moderate pollution, but spikes during festivals & traffic demand stricter vehicular emission policies.

Kolkata → Seasonal peaks (festivals + winter). Requires festival-specific emission control.

Bengaluru → Comparatively better air, but rising trend due to rapid urbanization. Need for early green policies.

5. Actionable Policy Recommendations

Seasonal Controls: Pre-winter alerts, stricter emission norms before stubble burning and festival seasons.

Transport Interventions: Promote EVs, stricter checks on diesel vehicles, encourage public transport.

Green Zones: Expansion of urban green belts to improve air filtration.

Awareness Campaigns: Public warnings during high-AQI periods (especially in Delhi & Kolkata).

6. Final Outcome

Delivered city-wise breakdown of air pollution trends.

Generated 6–12 month forecasts with visualization outputs and CSV files.

This study highlights the severe and recurring air pollution challenges faced by major Indian cities, especially Delhi and Kolkata during winter months. Time series forecasting using Prophet and SARIMAX models successfully captured seasonal pollution trends, enabling short- and mid-term predictions. The insights generated can support policymakers in implementing targeted interventions to reduce emissions, protect public health, and promote sustainable urban growth.
Identified high-risk periods → mainly winter months in north India.

Produced a data-driven roadmap for policymakers with specific recommendations.
