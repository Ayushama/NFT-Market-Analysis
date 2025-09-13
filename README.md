## Project Overview
This project provides a comprehensive analysis of NFT market trends with detailed visualizations and predictive modeling. Daily NFT sales are analyzed and forecasted using **Prophet** and **ARIMA** models. The project is implemented entirely in **Python**.

## Features
- Exploratory Data Analysis (EDA) of NFT sales
- Visualizations including:
  - Daily sales (USD) over time
  - Cumulative sales (USD) over time
  - Primary vs Secondary sales (cumulative)
  - Daily number of sales
  - Distribution of daily sales and number of sales
  - Correlation matrix of key metrics
- Time series forecasting of NFT sales using:
  - Prophet model
  - ARIMA model
- Evaluation metrics for forecasts:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

## Technologies
- Python
- pandas, numpy, matplotlib, seaborn
- scikit-learn, statsmodels
- Prophet
- Jupyter Notebook


## Data

* The dataset includes daily NFT sales data with columns like `Date`, `Sales_USD`, `Number_of_Sales`, `Primary_Sales`, etc.
* Ensure the dataset CSV file is in the same directory as the notebook or update the path accordingly.

## Results

* Provides visual insights into NFT market trends.
* Forecasts future sales for 30 days beyond the dataset.
* Compares Prophet and ARIMA models for prediction accuracy.

## Author

[Ayush Aman](www.linkedin.com/in/ayush-aman-039817161)





