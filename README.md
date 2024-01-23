# Yes Bank Stock Closing Price Prediction

Predicting the closing stock prices of Yes Bank based on historical data, including open, high, low, and close prices. The project explores the impact of a fraud case involving Rana Kapoor on the stock prices and aims to provide insights for investors and analysts.

![Decoding-Collapse](https://github.com/jay-p007/Yes-Bank-Stock-Closing-Price-Prediction-Capstone-Regression-Project/assets/154582415/fdaec078-3ebe-4160-812d-e1860979e3bd)

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)
- [Data Source](#Data-Source)
- [Models](#models)
- [Charts and Visualizations](#charts-and-visualizations)
- [Conclusion and Future Considerations](#Conclusion-and-Future-Considerations)

## Overview

The project analyzes the impact of a fraud case involving Rana Kapoor on the stock prices of Yes Bank. It utilizes historical stock price data, including monthly open, high, low, and close prices, to predict the closing stock prices. The models implemented include Ridge Regression, Random Forest, and XGBoost Regressor. Insights gained from these models help investors and analysts make informed decisions.

## Usage 
To explore the findings and insights, refer to the Colab Notebooks provided in the GitHub repository.

## Data Source
To access the Data: [Click Here](https://drive.google.com/file/d/1qE-lEu9VDFTQ26ivGoBpg4Ztoe1sek7f/view)

## Models

### Linear Regression

Linear Regression is a fundamental machine learning algorithm used for predicting a continuous target variable based on one or more predictor variables. In this project, Linear Regression was employed to establish a baseline prediction model for the stock closing prices.

### Ridge Regression (L2 Regularization)

Ridge Regression is an extension of Linear Regression that includes a regularization term to prevent overfitting. It adds a penalty term to the loss function, helping to shrink the coefficients towards zero. Ridge Regression was used to enhance the predictive performance of the Linear Regression model and mitigate overfitting.

### Random Forest Regressor

Random Forest is an ensemble learning method that builds a multitude of decision trees during training and outputs the average prediction of the individual trees. In this project, Random Forest Regressor was utilized to capture complex relationships within the stock price data and improve prediction accuracy.

### XGBoost Regressor

XGBoost (Extreme Gradient Boosting) is a powerful gradient boosting algorithm that has proven effective in various machine learning tasks. XGBoost Regressor was chosen for its ability to handle complex relationships, feature interactions, and non-linear patterns in the stock price data.

### Model Comparison and Selection

The models were evaluated based on metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R-squared (R2), and Adjusted R-squared. The final selection was made considering the trade-off between model complexity, interpretability, and predictive performance.

## Charts and Visualizations

### 1. RSI (Relative Strength Index)

The RSI chart depicts the Relative Strength Index, a momentum oscillator that measures the speed and change of price movements. This helps in identifying overbought or oversold conditions, aiding in potential trend reversal predictions.

### 2. MACD (Moving Average Convergence Divergence)

The MACD chart visualizes the Moving Average Convergence Divergence, a trend-following momentum indicator. It helps identify potential trend changes and provides signals for buying or selling decisions.

### 3. Candlestick Chart

The Candlestick Chart represents stock prices using candlestick patterns, providing information about open, high, low, and close prices for each time period. Analyzing candlestick patterns helps in understanding market sentiment and potential trend reversals.

### 4. Moving Average Chart

The Moving Average Chart displays the average closing prices over a specified period. It smoothens out price fluctuations, making it easier to identify trends. The intersection of different moving averages can signal potential entry or exit points for traders.

## Conclusion and Future Considerations

### Conclusion

In conclusion, the stock price prediction project for Yes Bank provided valuable insights into the impact of a fraud case on stock prices. The use of machine learning models, including Ridge Regression, Random Forest, and XGBoost, helped in understanding and predicting stock movements. The models demonstrated varying performance, with Ridge Regression standing out as the most effective.

Key Findings:
- Ridge Regression showed superior performance in predicting stock prices.
- Feature importance analysis highlighted the significant role of certain features in influencing stock prices.
- The project successfully captured patterns and trends in the stock market related to the fraud case involving Rana Kapoor.

### Future Considerations

For future enhancements and considerations, the project can explore the following areas:

1. **Feature Engineering:**
   Further refine and experiment with additional features to capture more complex patterns in stock price movements.

2. **Hyperparameter Tuning:**
   Conduct more extensive hyperparameter tuning to optimize the models further and improve their predictive capabilities.

3. **Ensemble Models:**
   Investigate the use of ensemble models, combining the strengths of different algorithms to enhance overall performance.

4. **Real-time Data Integration:**
   Implement a system to fetch real-time data, enabling the models to make predictions based on the market information.

By addressing these considerations, the project can evolve and provide even more accurate and timely predictions for stock prices, contributing to informed decision-making in the financial domain.
