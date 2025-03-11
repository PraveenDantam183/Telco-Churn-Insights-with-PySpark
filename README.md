# Telco Churn Insights with PySpark

## Overview
This project analyzes customer churn in a telecom dataset using PySpark. I sourced the Telco Customer Churn dataset (7,043 records) from Kaggle to identify patterns that can help reduce churn.

## Features
- Loads and cleans the dataset, addressing issues like missing values.
- Uses window functions to rank high-risk customers and track churn trends.
- Joins with a subscription catalog, optimizing with broadcasting.
- Visualizes churn rates and average charges with Matplotlib.

## How to Run
- Open `Customer_Churn_Analysis.ipynb` in Google Colab.
- Install PySpark with `!pip install pyspark`.
- Execute all cells.

## Skills Demonstrated
- PySpark DataFrame APIs
- Window functions (`rank`, `sum`)
- Joins and optimization
- Data visualization
