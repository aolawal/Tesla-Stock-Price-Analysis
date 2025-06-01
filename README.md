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

*Notebook showing the comprehensive details attached *

## Project Outcomes / Findings:
- Using FB Prophet, the Upper and Lower Band was able to give a near perfect prediction of the price movement between 2020 and 2024 until towards the end of 2024 when there was significant deviation of the predcition form actual price movement. On few occassions the deviation between the actual price and Lower band prediction was noticeable, such as the beginning of 2021, end of 2021 and beginning of 2022. The FB prophet seems to display a better result based on the chart above compared to Matplotlib chart. As earlier explained, the deviation toward the end of 2024 was due to increased market confidence after announcement of US election result. While the deviation in the beginning of year 2025 was due to negative sentiment towards TSLA share price as a result of involvement of Elon Musk in US politics and the announcement of new tariff regime by US government at the beginning of 2nd Quarter of 2025.

<img width="625" alt="TSLA 2" src="https://github.com/user-attachments/assets/0c58aa8c-b546-4fc7-8146-863c12907317" />
