# Store Sales Forecasting 

# Store Sales Forecasting

## Team 7: Nishita Matlani & Dhir Thacker

This project focuses on forecasting retail sales to navigate the challenges of retail management in a fluctuating economic environment heavily dependent on oil prices.

### Table of Contents
1. [Introduction](#introduction)
2. [Motivation](#motivation)
3. [Goals](#goals)
4. [Methodology](#methodology)
5. [Dataset Description](#dataset-description)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Results and Analysis](#results-and-analysis)
9. [Conclusion](#conclusion)
10. [References](#references)

---

## Introduction

In Ecuador, where the economy is significantly influenced by oil prices, the retail sector faces challenges in matching supply with fluctuating demand. Our project develops predictive models that forecast retail sales by analyzing historical sales data, promotional activities, and external factors such as oil prices and holidays.

## Motivation

The project aims to empower businesses to make informed decisions on inventory and promotions, adapting in real-time to market demands using data science and machine learning.

## Goals

Our objective is to create a predictive tool that offers daily sales predictions across various store fronts and product lines, optimizing operations and enhancing profitability.

## Methodology

### Data Cleaning and Preprocessing
- **Load and merge datasets:** Combine sales data, store information, transaction records, oil prices, and holiday/event data.
- **Handle missing values and duplicates:** Ensure data quality by cleaning the dataset thoroughly before analysis.

### Exploratory Data Analysis (EDA)
- Conduct a comprehensive EDA to identify key patterns and relationships in the data.

### Feature Engineering
- Develop features like 'Year', 'Month', 'Weekday', lag features, and rolling averages to improve model predictions.

### Modeling
- Use models such as Linear Regression, Random Forest, Decision Trees, and XGBoost.

### Model Evaluation
- Evaluate models based on RMSE and MAE to determine the best performer.

## Dataset Description

We utilize five CSV files with a total of 14 different columns including store number, product type, sales data, and external factors like oil prices and holidays.

### Files
- `train.csv`
- `test.csv`
- `sample_submission.csv`
- `stores.csv`
- `oil.csv`
- `holidays_events.csv`

## Installation

```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt
