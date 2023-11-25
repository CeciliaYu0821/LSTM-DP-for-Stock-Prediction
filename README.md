# Differential Privacy LSTM for Stock Prediction with Financial News
The project involved detailed sentiment analysis of financial news articles and sophisticated time series analysis of stock prices. It determined that LSTM models, reinforced with differential privacy (LSTM-DP), surpassed conventional time series models in forecasting accuracy with a 60% reduction in MSE due to their more robust feature integration.

## Project Structure
The project is organized into the following components:

- <strong> 'news_with_sentiment.csv': </strong> The dataset contains 3 columns - published_date, source_name (cnbc/fortune/reuters/wsj), and compound (compound score extracted from financial news articles via sentiment analysis).<br>

- <strong> 'Project_all_models.ipynb.': </strong> The notebook contains the entire steps taken in the data analysis process.<br>
_Data Preprocessing_  - Extract S&P 500, Nasdaq 100 Index, the Dow Jones Industrial Average, and the Russell 2000 Index from Yahoo Finance API. Calculate the daily compound sentiment scores of four sources, respectively.<br>
_Model Constructure_  - Build a suite of 3 models (ARIMA, Random Forest, and LSTM with/without sentiment/DP). <br>
_Model Evaluation_  - Evaluate the performance of the constructed models based on MSE, R-square, and accuracy.

- <strong> 'Project Report.pdf' </strong> The final report of the project. <br>
 
 - <strong> 'Slide.pdf' </strong> The slide presented at class. 

## Conclusions
The LSTM model outperformed ARIMA and Random forest for index time series prediction. All time series models work better on the return data as it is normalized with the same scale. LSTM with DP would achieve the best performance in most scenarios as the features it takes would be more robust.

## Contact Information
If you have any questions, please contact [simin.yu@columbia.edu].

