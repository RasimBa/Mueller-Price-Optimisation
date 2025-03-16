# Mueller Price Optimization

## Project Overview
This project focuses on optimizing revenue for Mueller yogurt products by analyzing how price, product attributes, and seasonality affect sales. The goal is to develop a predictive model to estimate sales based on price and other factors, and to simulate different pricing strategies to maximize revenue.

## Data Description
The project uses two datasets:
- **Product Data (`data_files/product.csv`)**: Contains details about yogurt products, including product ID, brand, flavor, volume, and pack size.
- **Sales Data (`data_files/sales.csv`)**: Contains daily sales data, including date, price, units sold, and revenue.

## Methodology
1. **Exploratory Data Analysis (EDA)**: Examines price trends, revenue patterns, and sales behavior across different flavors and time periods.
2. **Predictive Modeling**: A log-linear regression model is used to predict units sold based on price, product attributes, and day of the week.
3. **Revenue Optimization Simulation**: The model is used to test different pricing strategies and estimate their impact on sales and revenue.

## Repository Structure

Mueller-Price-Optimisation/
│── data_files/
│   ├── sales.csv
│   ├── product.csv
│── jupyter_files/
│   ├── Mueller Price Optimisation.ipynb
│── README.md


## Usage
1. Run the Jupyter notebook `jupyter_files/Mueller Price Optimisation.ipynb` to explore the data and build the model.
2. Modify test prices in the simulation section to analyze the impact of different pricing strategies.
3. Use the model's predictions to guide pricing decisions.
