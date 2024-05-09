# Store Sales Forecasting 

## Team 7: Nishita Matlani & Dhir Thacker

This project aims at creating a robust forecasting model to predict daily retail sales, enabling retailers to make informed decisions and optimize their operations in an economically volatile environment, primarily affected by fluctuating oil prices.

### Table of Contents
1. [Introduction](#introduction)
2. [Project Motivation](#project-motivation)
3. [Project Goals](#project-goals)
4. [Methodological Approach](#methodological-approach)
5. [Dataset Overview](#dataset-overview)
6. [Setup and Installation](#setup-and-installation)
7. [How to Use](#how-to-use)
8. [Detailed Results and Analysis](#detailed-results-and-analysis)
9. [Concluding Remarks](#concluding-remarks)
10. [References and Additional Resources](#references-and-additional-resources)

---

## Introduction

This project is centered around the challenges of retail management in Ecuador, a country where the economy is highly influenced by oil prices. These economic fluctuations impact consumer purchasing power, creating a volatile market for retailers. Our forecasting models are designed to predict sales with high accuracy, using historical sales data intertwined with promotional activities and economic indicators like oil prices and holidays.

## Project Motivation

The motivation behind this project is to empower retailers with predictive insights that allow them to stay ahead in a rapidly changing market. By integrating advanced data analytics and machine learning techniques, we transform raw data into actionable insights that drive strategic business decisions.

## Project Goals

The goal is to develop a sophisticated predictive tool that not only adapts to but also anticipates market changes, providing clear, actionable daily sales predictions. This tool is expected to enhance operational efficiency and profitability across various retail outlets.

## Methodological Approach

### Data Preparation
- **Data Cleaning:** Initial steps include loading the data into a suitable format, removing duplicates, and correcting inconsistencies.
- **Handling Missing Data:** Techniques such as interpolation for continuous variables and imputation for categorical variables are used to address gaps in the dataset.

### Exploratory Data Analysis (EDA)
- **Visual Analytics:** Utilizing plots like histograms, scatter plots, and box plots to understand distributions and relationships.
- **Statistical Analysis:** Conducting correlation analysis and hypothesis testing to validate assumptions and insights.

### Feature Engineering
- **Temporal Features:** Incorporation of time-based features to capture seasonal and cyclical patterns.
- **Advanced Features:** Developing lag features and rolling averages to better capture trends and smooth out noise in the data.

### Model Development and Evaluation
- **Model Selection:** Employing various statistical and machine learning models including Linear Regression, Random Forest, and XGBoost.
- **Performance Metrics:** Using RMSE and MAE for quantitative model evaluation, alongside visual comparisons of predicted vs. actual sales data.

## Dataset Overview

We utilize a comprehensive set of data from various sources, structured into several CSV files as described below:

### Data Files
- `train.csv` - Training dataset with historical sales data.
- `test.csv` - Test dataset used for model evaluation.
- `sample_submission.csv` - A template for submitting predictions.
- `stores.csv` - Information about store types and locations.
- `oil.csv` - Daily oil prices as an economic indicator.
- `holidays_events.csv` - Details on holidays and events affecting sales.

## Setup and Installation

To set up the project environment:

```bash
# Clone the repository
git clone <repository-url>
# Navigate to the project directory
cd <repository-name>
# Install required Python packages
pip install -r requirements.txt

