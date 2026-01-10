# BradfordSkyRain – Visual Analytics & ML for Solar Radiation + Rainfall Forecasting in Bradford

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)

**Local weather forecasting using 1 year of half-hourly sensor data from the University of Bradford weather station.**

Predicting solar radiation (for renewable energy planning) and rainfall intensity (for urban resilience) with interpretable Random Forest models + beautiful visualisations.

### 🌟 Key Results
- **Solar Radiation Forecasting**  
  R² = **0.815** | MAE = **19.76 W/m²**  
  UV_Index dominates predictions (importance 0.857) – perfect for photovoltaic insights

- **Rainfall Intensity Classification**  
  Overall Accuracy = **93%** (cross-validated **96.3% ± 2.1%**)  
  Perfect recall on "No Rain" | Top predictors: humidity & pressure trends

### What You'll Find
- Stunning visualisations of seasonal patterns, correlations, and extreme events  
- Feature importance & actual vs predicted plots  
- Full Jupyter notebook with data cleaning, feature engineering & models  
- Honest discussion of class imbalance challenges in heavy rain detection

### Gallery of Results

**Daily & Seasonal Patterns**  
![Daily Averages](screenshots/daily_averages1.png)  
![Temperature + Solar Over Time](screenshots/temp_solar_timeseries1.png)

**Correlations & Extremes**  
![Correlation Heatmap](screenshots/correlation_heatmap1.png)  
![Heavy Rain Days](screenshots/heavy_rain_extremes1.png)  
![Extreme Solar Days](screenshots/extreme_solar_extremes1.png)

**Model Performance**  
![Solar Actual vs Predicted](screenshots/solar_actual_vs_predicted1.png)  
![Solar Feature Importance](screenshots/solar_feature_importance1.png)  
![Rainfall Confusion Matrix](screenshots/rain_confusion_matrix1.png)  
![Rainfall Feature Importance](screenshots/rain_feature_importance1.png)

### Project Structure
