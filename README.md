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

## Screenshots
<img width="1097" alt="Screenshot 2024-03-06 at 6 50 07 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/db519453-b39f-4f64-a349-2169814d4d07">

<img width="1094" alt="Screenshot 2024-03-06 at 6 50 26 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/82c98764-543f-40ad-861e-a08ef7633726">

<img width="1081" alt="Screenshot 2024-03-06 at 6 52 04 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/78032518-f4be-453a-8cb7-2f845da2a148">

<img width="1111" alt="Screenshot 2024-03-06 at 6 54 17 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/610ab2b7-7cc0-4ae6-826f-f488f722b35e">

<img width="1088" alt="Screenshot 2024-03-06 at 6 56 48 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/49dd8144-f568-4e43-89cf-e17592f90703">

<img width="1075" alt="Screenshot 2024-03-06 at 7 02 34 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/f1d2ff53-6308-450c-a7ce-e022adc5522e">


## References

- [Statsmodels Documentation](https://www.statsmodels.org/stable/index.html)
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/)
