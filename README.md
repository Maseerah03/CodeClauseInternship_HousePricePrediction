# Project Overview

In this project, we're predicting future house prices.  We're using data from the Federal Reserve, along with house price data from Zillow.  We're merging and combining this data, then using it to train a random forest model.  The model will predict if house prices will increase or decrease in the future.  We're measuring error using backtesting, then improving our model with new predictors.


**Project Steps**

* Load in data
* Clean and merge data
* Create an initial machine learning model and estimate accuracy
* Improve the accuracy of the model
* Run diagnostics to figure out how we can improve


File overview:

* `House Price Prediction.ipynb` - a Jupyter notebook that contains all of the code.

# Local Setup

## Installation

To follow this project, we have installed the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * yfinance
    * scikit-learn

## Data

We've downloaded a few csv files to run this project.  

* Federal reserve data
    * [CPI dataset](https://fred.stlouisfed.org/series/CPIAUCSL) - CPIAUCSL.csv
    * [Rental vacancy rate](https://fred.stlouisfed.org/series/RRVRUSQ156N) - RRVRUSQ156N.csv
    * [Mortgage interest rates](https://fred.stlouisfed.org/series/MORTGAGE30US) - MORTGAGE30US.csv
* [Zillow data](https://www.zillow.com/research/data/)
    * ZHVI (raw, weekly) - Metro_zhvi_uc_sfrcondo_tier_0.33_0.67_month.csv
    * Median sale price (raw, all homes, weekly) - Metro_median_sale_price_uc_sfrcondo_week.csv
