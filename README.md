# Daily Revenue Forecasting

## Overview

This project analyzes seasonal trends and patterns in sales data using time series analysis techniques.

## Key Insights

- **Yearly Spikes:** Significant peaks at the end of each year (possibly due to holidays).
- **Trend Analysis:** The data shows an upward trend before stabilizing.
- **Seasonality:** Clear repetitive cycles, especially in November.
- **Quarterly Trends:** Q3 and Q4 show higher activity.
- **ADF:** Used Augumaented Dicky Fuller Test to check Stationarity
- **Differencing:** Performed Differencing to make the data stationary

## Files & Structure

- `notebook.ipynb` – Full analysis with plots and explanations.
- `data/` – Raw and processed data files.
- `visualizations/EDA` - All the visualizations of EDA
- `visualizations/EDA` - All the visualizations of Forecasting model
- `notebooks/models.ipynb` - contains models like `ARIMA`, `SARMIA`,`SARIMAX`

## Model Performance

## ARIMA

- `MAE`: 7267306.024263437
- `RMSE`: 12366038.29993861
- `MAPE`: 0.241461145875348

## SARMIA

- `MAE`: 7210543.983525436
- `RMSE`: 12152386.469468849
- `MAPE`: 0.24536495629219485

## SARIMAX

- `MAE`: 5716327.042129176
- `RMSE`: 10394396.812419357
- `MAPE`: 0.19359098435175184

### CrossValidation and FineTuned Sarimax

## How to Run the Project

- Clone the repository

```bash
https://github.com/anandreddy05/Daily_Revenue_Forecasting 
```

```bash
cd Daily-Revenue
```

```bash
pip install -r requirements.txt
```

### Future Enhancements

- Experiment with Prophet, and LSTM models
- Improve hyperparameter tuning for better forecasts
- Deploy as a real-time forecasting app
📢 Contributions are welcome! Feel free to fork, modify, and submit a pull request.
