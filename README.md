# Analyzing Amazon’s Revenue: Exploring Forecasting Models

This repository presents a comprehensive analysis of Amazon's revenue forecasting for the fiscal year 2021. The objective was to analyze historical revenue data from 2010 to 2020 and identify the most suitable forecasting model that accurately predicts Amazon's revenue trends. To achieve this, we employed various trend regression models with seasonal dummy variables and the Holt-Winters Exponential smoothing method to uncover patterns and seasonal fluctuations within Amazon's revenue stream.

We utilized cross-validation techniques, dividing the data into a training set (2010 – 2018) and a validation set (2019 – 2020), to identify the optimal forecasting approach. We explored various Trend regression models, including linear, exponential, quadratic, and cubic on the training set to determine their effectiveness in forecasting Amazon's revenue. Additionally, we implemented the Holt-Winters exponential smoothing model, by fine-tuning parameters to optimize the forecasting accuracy. This involved minimizing the Root Mean Squared Error (RMSE) between actual and forecasted values using optimization techniques like Solver in Excel.

After evaluating the performance of each model on the validation set, we found that the Holt-Winters exponential smoothing model outperformed other models in terms of accuracy with the lowest Mean Squared Error (MSE), Mean Absolute Deviation (MAD), and Mean Absolute Percentage Error (MAPE), indicating superior forecasting accuracy.

Using the Holt-Winters model, we forecasted Amazon's revenue for the fiscal year 2021, with quarterly revenue projections, enabling investors to make informed decisions based on reliable insights into Amazon's financial performance.

#### Comprehensive Report:
[Amazon Revenue_Time Series Forecasting.pdf](https://github.com/srimallipudi/Analyzing-Amazon-s-Revenue-Exploring-Forecasting-Models/files/14780664/Amazon.Revenue_Time.Series.Forecasting.pdf)
