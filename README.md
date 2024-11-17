# Time Series Forecasting with Prophet and ARIMA Models

This repository contains a comprehensive workflow for time series forecasting using advanced statistical and machine learning techniques, including the **Prophet** library and **ARIMA** models. The code handles dataset preprocessing, normalization, interpolation, and forecasting with exogenous variables.

---

## Features

- **Dataset Handling**: Preprocesses time series data, including date conversion and setting a datetime index.
- **Data Normalization**: Implements `StandardScaler` for feature normalization.
- **Data Interpolation**: Interpolates missing data points using time-based methods.
- **Prophet Library**:
  - Exogenous variable support for enhanced forecasting.
  - Seasonal adjustments with custom Fourier transformations.
- **ARIMA Models**: Integrates traditional time series modeling techniques like ARIMA and SARIMAX.

---

## Requirements

Ensure the following Python packages are installed:

```bash
pip install -U -q PyDrive pandas numpy matplotlib seaborn statsmodels fbprophet
git clone https://github.com/<your-username>/time-series-forecasting.git
cd time-series-forecasting
pip install -r requirements.txt
python forecasting_script.py

Replace `<your-username>` with your GitHub username before uploading.
