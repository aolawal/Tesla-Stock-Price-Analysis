# Tesla-Stock-Price-Analysis
# Trend Analysis and Forecasting of Tesla Stock Price
## Project Overview
### The project aims to:
- etablish Tesla stock price movement by conducting a trend Analysis of TSLA Stock performance and forecasting TSLA stock price using FB prophet
- ascertain the return on investment (ROI) of multiple Electric vehicle stocks (namely TSLA, GM and Ford) with a view to select the most profitable stock to invest in by comparing the stocks ROI over a 5-year period. (*2020 - 2025*)

## Procedure:
- The necessary libraries were imported
- The timeframe of the data to be downloaded from Yahoo Finance was defined and the necessary Ticker symbol was inserted for loading
- The datasets were preprocessed to prepare the data for analysis (index was reset, necessary data were extracted
- The datasets were imported from Yahoo Finance and aggregated
- The model was trained to fit the prepocessed data using FB Prophet
- The model was evaluated to detect anomalies
- The model was used to predict the price of TSLA stock using Matplotlib and FB prophet.
