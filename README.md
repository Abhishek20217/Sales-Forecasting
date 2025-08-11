# Sales Forecasting Analysis
## Project Overview

This Project analyses Walmart's historical sales data forecasts future sales trends using the **time series analysis** techniques. Here **ARIMA** and **SARIMAX** is used for seasonal and trend patterns. The goal will be to help the shop retailers know which products are in demand, optimise inventory, and improve revenue planning.

## Objectives

* **Data Preparation & Stationarity Testing**: Process historical sales data from **2014–2018** and perform the Augmented Dickey-Fuller (ADF) test to confirm stationarity.
* **Model Selection** : **ARIMA** and **SARIMA** are used and **SARIMA** since the data is continous and having seasonal pattern.
* **Forecasting**: Predict sales for the next **four years (2018–2021)** to support strategic decision-making.

## Key Features

* **Stationarity Analysis**: Achieved strong stationarity with an **ADF Statistic** of **-5.40** and **p-value** of **3.327**, confirming suitability for **SARIMAX modelling**.
* **Model Selection Justification**: SARIMAX chosen over ARIMA due to the presence of strong **seasonal trends**.
* **Forecasting**: Generated accurate multi-year forecasts, revealing peak demand seasons.
* **Visual Insights**: Created visualisations after **training and testing the dataset** and using the same to **forecast** using SARIMAX model to show the model performance.

## Tools and Technologies

* **Python**: Data processing, modelling, and visualisation.
* **Jupyter Notebook**: Interactive analysis and reporting.
* **Pandas**: Data cleaning and manipulation.
* **Matplotlib**: Visualisation of trends and forecasts.
* **ARIMA & SARIMAX**: Time series forecasting.

## Results
**SARIMAX model** captured seasonal peaks and drops effectively, achieving an **89% forecast accuracy**.
**Forecasted** **sales trends** for **2018–2021** highlighted critical high-demand periods for inventory planning.

## Python file
<a href ="https://github.com/Abhishek20217/Sales-Forecasting/blob/main/Sales%20Forecasting.ipynb"> Viw file </a>
