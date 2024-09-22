# Domino's Predictive Purchase Order System

## Project Overview

The Domino's Predictive Purchase Order System is a time series forecasting project designed to predict pizza sales and generate corresponding purchase orders for ingredients. This system leverages various forecasting models to predict sales and subsequently calculate ingredient requirements to ensure optimal inventory management.

## Features

- **Data Preprocessing:** Cleans and prepares historical sales data for analysis.
- **Exploratory Data Analysis (EDA):** Analyzes trends, seasonality, and significant patterns in the sales data.
- **Sales Forecasting:** Implements ARIMA/SARIMA, Facebook Prophet, and LSTM models to forecast future pizza sales.
- **Purchase Order Generation:** Calculates ingredient quantities based on sales forecasts and generates purchase orders.
- **Model Evaluation:** Assesses model performance using metrics like Mean Absolute Percentage Error (MAPE).

## Usage

- Data Preprocessing: Run preprocess.py to clean and preprocess the data.
- Exploratory Data Analysis (EDA): Execute eda.py to generate visualizations and insights.
- Sales Forecasting: Train and evaluate models by running forecasting.py.
- Purchase Order Generation: Generate the purchase order with generate_order.py.
- Results: Review the results in the generated reports and files.

## Data
- The dataset includes historical sales data with timestamps. It should be placed in the data/ directory.

## Modeling
- ARIMA/SARIMA: Implemented using statsmodels.
- Facebook Prophet: Used for handling seasonality and holidays.
- LSTM: A neural network model built with TensorFlow for capturing complex patterns.

## Results
- The project generates:
- Preprocessed Dataset: Saved as cleaned_data.csv.
- EDA Report: Visualizations and insights in eda_report.html.
- Predictive Model: Saved models and evaluation metrics.
- Purchase Order: Ingredient quantities detailed in purchase_order.csv.
