# Copper Price Analysis

This Jupyter notebook analyzes the historical prices of copper and provides forecasts for future prices. It also offers policy recommendations based on the projected scenarios.

## Introduction
The notebook aims to analyze historical copper prices and forecast future prices using different modeling techniques. This analysis is crucial for stakeholders in the mining industry, policymakers, and investors.

## Data Description
The notebook uses historical copper price data, which is loaded and preprocessed for analysis. Key steps include handling missing values, normalizing data, and splitting it into training and testing sets.

## Analysis and Modeling
Two primary modeling techniques are used to forecast copper prices:
1. **Exponential Smoothing (ES):** A time series forecasting method that applies weighted averages of past observations.
2. **Neural Network (NN):** A machine learning model trained on the historical price data.

The models are evaluated using the Mean Squared Error (MSE) metric to determine their accuracy.

## Forecasting
Based on the models' performance, future prices are forecasted. Different growth scenarios are considered:
- **Strong Growth:** 20% increase in price.
- **Moderate Growth:** 10% increase in price.
- **Weak Growth:** 10% decrease in price.

## Policy Recommendations
The analysis concludes with several policy recommendations:
1. Increase recycling efforts to make use of economically viable copper prices.
2. Invest in research for alternative materials to copper.
3. Build strategic reserves to stabilize supply, especially for countries like China.
4. Promote sustainable mining practices globally.
5. Invest in R&D for technologies that use copper efficiently.

## How to Use
1. Clone or download the repository containing this notebook.
2. Ensure you have the necessary dependencies installed (see below).
3. Open the notebook in Jupyter and run the cells sequentially to reproduce the analysis.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Keras (for Neural Network model)

You can install the dependencies using the following command:
```bash
pip install pandas numpy matplotlib scikit-learn statsmodels keras
```
