# FoodHub Order Analytics

## Overview
This MIT IDSS data analytics project explores restaurant order data from FoodHub, an online food delivery platform. The analysis identifies customer ordering behavior, cuisine demand patterns, restaurant performance, delivery time trends, and revenue opportunities.

The dataset contains 1,898 orders and 9 features.

## Dataset
- Source: MIT IDSS project dataset
- File: `foodhub_order.csv`
- Size: 1,898 rows × 9 columns
- Data includes: order ID, customer ID, restaurant name, cuisine type, order cost, rating, food preparation time, delivery time, and day of week

## Key Methods
- Exploratory data analysis
- Data type inspection
- Missing value checks
- Univariate and bivariate analysis
- Visualization of cuisine demand and delivery trends
- Revenue calculation
- Business recommendation generation

## Key Findings
- American, Chinese, and Italian cuisines showed strong demand.
- Some restaurants met criteria for promotional offers based on rating count and average rating.
- A portion of orders took more than 60 minutes from preparation to delivery.
- Delivery and preparation trends can support operational optimization.

## Tech Stack
Python, pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## How to Run
pip install -r requirements.txt
jupyter notebook notebooks/foodhub_order_analytics.ipynb

## Project Structure
```text
.
├── README.md
├── requirements.txt
├── notebooks/
│   └── foodhub_order_analytics.ipynb
├── data/
│   └── README.md
└── figures/
