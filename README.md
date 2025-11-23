Montgomery County Crime Analytics: End-to-End Data Science Project

A complete analytics and machine-learning workflow for real Montgomery County (USA) crime incident data.
This project includes data cleaning, spatial and temporal analysis, classification, clustering, forecasting, and an interactive dashboard.

Tech: Python, Pandas, Scikit-learn, Statsmodels, Plotly, Dash, Streamlit, Jupyter

What this project does
1. Data Cleaning & Feature Engineering

Standardises and validates 280,708 crime records

Fixes timestamps, geolocation, duplicates, missing values

Creates engineered features: duration, report delay, hour, day, month, etc.

2. Spatial Hotspots

District-level crime analysis

Ranking of high-risk areas

Geo-map of >200k incidents

3. Temporal Crime Trends

74-month time series (2016–2022)

Monthly, weekday, and hour-of-day patterns

Crime type fluctuations over time

4. Crime Type Classification (TF-IDF + Logistic Regression)

Trains on 224k samples

Uses unified text fields

Accuracy: 1.0000 (perfect separation)

Fully diagonal confusion matrix

5. Severity Prediction (Crime Against Person)

Binary classification using numeric + categorical features

Logistic Regression accuracy ≈ 0.998

Random Forest nearly perfect

Top predictors: NIBRS code, offence code, victim count, reporting delay

6. Unsupervised Clustering (KMeans)

274k usable points

6 behavioural clusters

Distinct spatial, temporal, and incident-type patterns

7. Crime Forecasting (SARIMA vs Naive)

62-month training window → 12-month test window

Naive RMSE ≈ 870.8

Seasonal Naive RMSE ≈ 886.1

SARIMA RMSE ≈ 906.7 (structural breaks dominate)

District-level forecasting included (Silver Spring, Wheaton, Montgomery Village)

8. Interactive Dash & Streamlit Dashboard

Filters for date range, crime type, and district

KPIs, monthly trend, district ranking

Interactive Mapbox map with hover tooltips

Clean layout for real-world reporting
