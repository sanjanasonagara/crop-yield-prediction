# Crop Yield Prediction 

Predicting agricultural yield for Wheat and Rice across Indian states (2000–2018)
using weather conditions, fertilizer, and pesticide data.

## Models Used
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- SHAP (feature importance & explainability)

## Dataset
- `crop_yield.csv` — crop-wise yield data by state and year
- `state_weather_data_1997_2020.csv` — state-level weather data (temperature, rainfall, humidity)

## Features
- Temperature, Rainfall, Humidity
- Fertilizer and Pesticide usage
- State and Year

## How to Run
1. Clone the repository
2. Open `crop_yield_prediction.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells in order

## Requirements
```
numpy, pandas, matplotlib, seaborn, scikit-learn, xgboost, shap
```