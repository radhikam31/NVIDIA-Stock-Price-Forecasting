# NVIDIA Stock Price Forecasting and Strategic Recommendations

## Overview
This project analyzes NVIDIA's historical stock prices and builds forecasting models to evaluate future price trends. The project compares a time series linear regression model with exponential smoothing techniques to determine the most effective forecasting approach.

## Objective
The main goals of this project were:
- To visualize NVIDIA's historical adjusted closing prices and identify trends
- To build predictive models using linear regression and exponential smoothing
- To compare model performance using MSE and MAPE
- To provide forecasting recommendations based on model accuracy

## Project Summary
NVIDIA has shown strong growth along with significant stock price volatility. Because of this, investors and stakeholders need reliable forecasting methods to support investment decisions and risk management.

This project uses historical adjusted closing price data and applies:
- Time series visualization
- Linear regression
- Exponential smoothing

## Methods Used
### 1. Time Series Visualization
A time series plot was created to analyze NVIDIA's adjusted closing price over time and identify trends and fluctuations.

### 2. Linear Regression
A time series regression model was built to measure price trend over time.

### 3. Exponential Smoothing
Exponential smoothing models were tested with alpha values:
- 0.2
- 0.8
- 0.9

The models were compared using:
- Mean Squared Error (MSE)
- Mean Absolute Percentage Error (MAPE)

## Key Results
### Linear Regression
- R-squared: 0.7525
- MSE: 127.44
- MAPE: 17.93%

### Exponential Smoothing
- Best model: alpha = 0.9
- MSE: 6.16
- MAPE: 2.36%

## Conclusion
The exponential smoothing model with alpha = 0.9 significantly outperformed the linear regression model for this dataset.

Because it had a much lower MSE and MAPE, it was the most accurate forecasting approach for NVIDIA stock prices in this analysis.

## Business Recommendation
Based on the findings, exponential smoothing is recommended for short-term forecasting of NVIDIA stock prices. This can help support:
- investment analysis
- market strategy decisions
- short-term planning under uncertainty

## Tools Used
- R
- RStudio
- Time Series Analysis
- Linear Regression
- Exponential Smoothing

## Files in This Repository
- `code/` contains the R scripts
- `data/` contains the dataset used in the analysis
- `images/` contains project charts and visualizations
- `Final_Project.pdf` contains the presentation slides

## Future Improvements
- Test ARIMA and other advanced forecasting models
- Use longer time horizons
- Add live stock data integration
- Build an interactive dashboard for forecast visualization

## Author
**Radhika Mandhanya**  
Business Analytics Student, San Jose State University
