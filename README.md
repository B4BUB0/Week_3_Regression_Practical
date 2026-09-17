# Week 3: Supervised learning — regression and model training

**Applied Machine Learning for Business**

Run cells from top to bottom. This notebook combines short numerical exercises with a stock-series practical. Use Python with `numpy`, `pandas`, `matplotlib`, and `scikit-learn` installed. Put `stock_data.csv` in the same working folder as this notebook. The supplied `.py` file runs the same code from its own folder.

## Dataset
Simulated stock price series from [mrsimple07, Stock Price Prediction (Kaggle)](https://www.kaggle.com/datasets/mrsimple07/stock-price-prediction). The file has 365 calendar dates and five unnamed series (`Stock_1` to `Stock_5`); it contains neither real company identifiers nor currency metadata. Treat the values as price units. The numbers reproduce multiplicative random walks generated with NumPy seed 0; they should not be described as genuine exchange observations. No network or price API is needed.

## Forecasting Question
After observing today's recorded `Stock_1` value, predict its value on the next recorded date. A correct prediction exercise does not establish a profitable investment strategy.

## Learning Goals
* Explain a regression equation and its errors
* Perform one gradient update
* Construct past-only features
* Separate training, validation, and final testing
* Compare linear regression and Ridge with a simple baseline