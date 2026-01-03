# Broadcast_Viewership_Forecasting_Project-

# Broadcast Viewership Forecasting (15-Day Horizon)

## Overview
Forecast average daily broadcast viewership up to 15 days ahead using historical audience patterns.

## Objective
- Predict upcoming high-viewership periods
- Support ad planning and content scheduling

## Method
- Lag & rolling features from historical viewership
- Direct multi-step regression (1–15 days ahead)
- Random Forest models
- No data leakage (future values never used as features)

## Example Forecast
![Forecast](plots/al_dhabia_fm_15day_forecast.png)

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib
