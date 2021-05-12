# StockMarketPredictionDataAnalysis

### Topic:
•	Stock Price Data Analysis and Prediction

### Course:
•	Data Science Engineering Methods and Tools


### Abstract
for the prediction of the stock market prices from the historical stock market data set from year 1970 to 2018 in the Unites States of America.
The dataset used in the project has been taken from the Kaggle. The data is then cleaned as per the business requirement and then various models were utilized in Jupyter Notebook to see which model is the good fit for accurate predictions.
After studying the dataset and understanding the data models, it became evidently clear that the problem statement to predict stock prices fall under the time-series and regression. The study focuses on the various algorithms by using regression such as Linear regression, decision tree regression, Regressor Gated Recurrent Unit and time series such as Recurrent Neural Network (LSTM= Long Short-Term Memory method).
The major finding is that the machine learning approach should be suitable for this problem due to many aspects.



### Background:
Stock price data analysis and prediction aims to predict the close price for the one of the top companies from the data set we have taken example of NYL& AAPL, the dataset is available for 1970 to 2018, for predicting the score we filtered the data to 2017 year. This system as ‘Close’ and ‘Adjusted Close Price’ as the target variable and its predictions are based on variety of intrinsic and contextual attributes such as ticker (company name), date, adj_close, open, high and volume.

### Motivation:
Stock price prediction is a classic and important problem. With a successful model for stock prediction, we can gain insight about market behavior over time, spotting trends that would otherwise not have been noticed. With the increasingly computational power of the computer, machine learning will be an efficient method to solve this problem. 
The motivated idea is that, if we know all information about today’s stock trading (of all specific traders), the price is predictable. Thus, if we can obtain an information from previous trends, we can expect to improve the current prediction lot.

Thus, our motivation is to design a system model incorporating historical data and price predictions to make a stronger model that will benefit everyone.
### Goal:
In the current emerging competitive market, predicting the stock prices as well as the company's financial status in advance will provide more benefits for the investors in order to invest confidently. Stock prediction can be done by using the current and previous data available on the market.

We wish to present this system model to predict the stock price trends for a company, by providing deep analysis on the close price in simpler visualizations formats for quick and easy understanding. Our goal is to get an outcome 
- demonstrate NLY company stock price prediction as an example to satisfy the customer
- Visualize various stock parameters such close and open price, high and volume
- Predict Adjusting closing price using LSTM
- Predict stock price for AAPL using LSTM




### Model Used:
Target variable we have used is ‘close’ and adj_close, both are the stock price of the ticker(company)
Below are the different types of Models utilized for the project are
Linear Regression
-	RegressorGRU(Gated Recurrent Unit)
-	Decision Tree Regression
-	Recurrent Neural Network (LSTM = Long Short-Term Memory method) 


### Dataset Source:
We have used below dataset from Kaggle:
Daily Historical Stock Prices (1970 - 2018) Historical stock prices for several thousand unique stock tickers (20.97 million records – 2GB data)
https://www.kaggle.com/ehallmar/daily-historical-stock-prices-1970-2018




### Data Analysis:
Since, we have a huge data set of 20 million, we extracted 1.29 million of data and did exploratory data analysis so that we can predict the model accurately. When analyzed we have found that there were null values in one of the files and we removed those NaN as well.

### Exploratory Data Analysis:

  #### Visualizing NASDQ and NYSE stocks count

![image](https://user-images.githubusercontent.com/25372409/117930028-58e11180-b2b2-11eb-9334-b2f51f714992.png)

  ### Finance Sector
![image](https://user-images.githubusercontent.com/25372409/117930046-5ed6f280-b2b2-11eb-9ecb-d3ece462903c.png)

  ### Sectors Sort by Ticker Exchange
  ![image](https://user-images.githubusercontent.com/25372409/117930150-8037de80-b2b2-11eb-8c94-4d73368ec811.png)

  ### Top 10 Industry
  ![image](https://user-images.githubusercontent.com/25372409/117930209-9180eb00-b2b2-11eb-90fd-0a197e9cb45f.png)
### Prediction Graphs

  ### Linear Regression 
  ![image](https://user-images.githubusercontent.com/25372409/117930282-a65d7e80-b2b2-11eb-89cf-66493c0ee684.png)
  
  ### Regressor GRU
  ![image](https://user-images.githubusercontent.com/25372409/117930334-b70df480-b2b2-11eb-896a-3814b1f30921.png)
![image](https://user-images.githubusercontent.com/25372409/117930371-c0975c80-b2b2-11eb-9b53-bbbe7104844a.png)

  ### LSTM 
  ![image](https://user-images.githubusercontent.com/25372409/117930455-dc026780-b2b2-11eb-8495-4eee80b2f1f8.png)
![image](https://user-images.githubusercontent.com/25372409/117930463-df95ee80-b2b2-11eb-98b2-bb9a40e64172.png) <hr>



### Steps to Run This Project  <br>
1. Clone or Fork this repo<br>
2. Download the data set from the link https://www.kaggle.com/ehallmar/daily-historical-stock-prices-1970-2018 <br>
3. Create data folder and place those files under that, kindly check file path wherever it is used <br>
4. Import necessary lib required which you might have not installed it <br>
5. Since the data is huge it will take a lot of time to load data <br>
6. You can adjust the date from when to when you want to extract the data, I have used 2017 year to extract the data and it was huge around 2 million records <br>
7. Running epoch process will be time consuming which is used in one of the algorithms, so if see your system is getting slow try to run this project in google colab <br>
8. Run all the cells at once using jupyter notebook <hr> <br>

### Developed By : Shivi Bhatt




