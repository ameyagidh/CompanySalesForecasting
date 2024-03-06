# CompanySalesForecasting

This project focuses on forecasting sales using the SARIMA (Seasonal Autoregressive Integrated Moving Average) model after performing EDA (Exploratory Data Analysis) on the data. SARIMA is a powerful time series forecasting technique that can handle data with both trend and seasonal components.

## Overview

In this project, we:
- Preprocessed the sales data
- Conducted exploratory data analysis (EDA) to understand the distribution of sales over time
- Checked for stationarity in the time series data
- Selected the best parameters for the SARIMA model using the AIC (Akaike Information Criterion)
- Trained the SARIMA model
- Evaluated the performance of the model using diagnostic plots and calculating the Root Mean Squared Error (RMSE)
- Generated out-of-sample forecasts for future sales values

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your_username/sales-forecasting.git](https://github.com/ameyagidh/CompanySalesForecasting.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the notebook `sales_forecasting.ipynb` to explore the code and reproduce the results.

## File Structure

The repository contains the following files:
- `sales_forecasting.ipynb`: Jupyter Notebook containing the code for sales forecasting using the SARIMA model.
- `prediction.csv`: CSV file containing the forecasted sales values.

## Results

The SARIMA model was trained on the sales data, and out-of-sample forecasts were generated for future sales values. The forecasted sales values are stored in the `prediction.csv` file.

## References

- [Statsmodels Documentation](https://www.statsmodels.org/stable/index.html)
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/)
