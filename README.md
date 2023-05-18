# Stock Market Price Predictor using Supervised Learning:

# Aim
To investigate various forecasting strategies for predicting future stock returns based on historical returns and numerical news indicators to create a portfolio that includes multiple stocks to diversify risk. We achieve this by understanding the seemingly disordered data from markets using supervised learning approaches for stock market predictions. The stock market fluctuates violently, and there are numerous complex financial indicators. However, technological advancements provide a possibility to profit consistently from the stock market and specialists in determining the most informative signs to make better predictions. The forecast of market value is critical for maximizing profit from stock option purchases while limiting risk to a minimum.

# Libraries used:
- Pandas: For creating and manipulating dataframes.

- Scikit Learn: For importing k-means clustering.

- Beautiful Soup and Requests: To scrap and library to handle http requests.

- Matplotlib: Python Plotting Module.

# Data Overview:
- Data Source --> Dataset/

- Data points --> 1493 rows

- Dataset date range --> October 2010 to September 2015

# Dataset Attributes:

- Close/Last - Close/Last Prices

- Volume - Volume of Stocks

- Open - Opening Prices of Stocks

- High - Highest Prices of Stocks

- Low - Lowest Prices of Stocks

# EDA(Exploratry Data Analysis)

The primary motive of EDA is to

- Examine the data distribution
- Handling missing values of the dataset(a most common issue with every dataset)
- Handling the outliers
- Removing duplicate data
- Encoding the categorical variables
- Normalizing and Scaling
### Here are some examples of data analysis we have done while exploring data

Data Visualization for all the correlation between Volume and Adj Close price

![Adj Close](https://github.com/Tayyba27/NewCode/assets/100337978/00f52633-8398-4c58-badd-86f1cc2706dc)



Data Visualization for all the columns for monthly wise

![date](https://github.com/Tayyba27/NewCode/assets/100337978/f760dfae-0db3-4cae-92ca-950fcac42b05)


Scatter PLot is Plotted between each Attribute(Trend) 


![visualization](https://github.com/Tayyba27/NewCode/assets/100337978/54b62e7b-7a7b-4e9a-b0a9-a216c37cb7cd)


# Data Modelling
After conducting exploratory data analysis, we began modeling in Python. So, for modeling, we applied Machine Learning techniques to the datasets to create a model that will generate output for stock price prediction.In this stage, we divided the data by 80% for training and 20% for testing. We used various algorithms and performed some parametric tuning during this procedure in order to improve the performance of our algorithms. 
- Linear Regression
- Neural networks
 
 
# LINEAR REGRESSION:
Linear Regression is a supervised learning algorithm in machine learning. It models a prediction value according to independent variables and helps in finding the relationship between those variables and the forecast and in this case we used last years dataset of companies to predict stocks value for future.

# Modeling And Deployment:
The model we choose finally is Linear Regression .It uses predicts the Closed Price of 21st day using past 20 days Close Price


![prediction](https://github.com/Tayyba27/NewCode/assets/100337978/af41db0e-0ac7-4996-befa-dcc11ac8af65)






