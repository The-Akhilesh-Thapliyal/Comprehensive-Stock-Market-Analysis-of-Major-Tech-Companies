# Stock Market Analysis of Tech Companies (AAPL, AMZN, GOOG, MSFT)

This project involves the analysis of stock data for four major tech companies: **Apple (AAPL)**, **Amazon (AMZN)**, **Google (GOOG)**, and **Microsoft (MSFT)**. The analysis covers various aspects of stock trends, moving averages, resampling, and correlation analysis over a 5-year period. The insights include visualization of stock prices, correlation between stocks, and resampled data at different time frequencies.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Steps Involved](#steps-involved)
   - [Visualizing Stock Price Trends](#1-visualizing-stock-price-trends)
   - [Calculating Moving Averages](#2-calculating-moving-averages)
   - [Resampling Stock Prices](#3-resampling-stock-prices)
   - [Analyzing Correlation Between Stocks](#4-analyzing-correlation-between-stocks)
   - [Visualizing Correlation of Daily Returns](#5-visualizing-correlation-of-daily-returns)
4. [Technologies Used](#technologies-used)

## Project Overview

The project focuses on analyzing stock data of the top four tech companies over a 5-year period. Using historical stock data, we investigate stock price trends, calculate moving averages, resample the stock prices at various frequencies, and analyze correlations between the daily returns of these companies.

## Dataset

The dataset consists of stock data from February 2013 to February 2018 for Apple, Amazon, Google, and Microsoft. Each dataset includes:
- **Date**: The date of the stock price
- **Open**: Opening price of the stock
- **High**: The highest price during the day
- **Low**: The lowest price during the day
- **Close**: Closing price of the stock
- **Volume**: The number of shares traded
- **Company Name**

## Steps Involved

### 1. Visualizing Stock Price Trends

The first step involves visualizing the stock price trends of the four companies over time, focusing on the closing prices. This helps in understanding the general trend of each company's stock over the given period.

![Stock Price Trends](https://github.com/user-attachments/assets/e1708f90-f5d5-480f-a25d-ce9fb34452ae)

### 2. Calculating Moving Averages

In this step, we calculate the moving averages for different window sizes (10, 20, 50 days). The moving average smoothens out the price data, allowing us to see trends more clearly.

![Moving Averages](https://github.com/user-attachments/assets/16bd8e3d-22c5-4532-af8c-6ed2bcba1b1a)

### 3. Resampling Stock Prices

The stock prices are resampled to analyze them at different frequencies:
- **Monthly Resampling**: Average closing price per month.
- **Yearly Resampling**: Average closing price per year.
- **Quarterly Resampling**: Average closing price per quarter.

These resampled data provide insight into stock performance at different intervals.

#### Monthly Resampling
![Monthly Resampling](https://github.com/user-attachments/assets/d65bf535-eade-418f-90c6-535d9faab06d)

#### Yearly Resampling
![Yearly Resampling](https://github.com/user-attachments/assets/87b56b83-42cd-4fe3-8c73-e0d511366280)

#### Quarterly Resampling
![Quarterly Resampling](https://github.com/user-attachments/assets/735f18c4-c381-4745-95c8-d2ad70c8a9f8)

### 4. Analyzing Correlation Between Stocks

Here, we investigate whether the closing prices of these companies are correlated. Pair plots are used to visualize the relationship between the companies' closing prices, and a correlation heatmap is plotted to display the correlation values.

#### Pair Plot of Closing Prices
![Pair Plot](https://github.com/user-attachments/assets/2d3090a6-78ca-41a0-b6ab-5fe8edfd0b91)

#### Correlation Heatmap
![Correlation Heatmap](https://github.com/user-attachments/assets/68f9054a-e692-4974-a9c3-427c83b51d6f)

### 5. Visualizing Correlation of Daily Returns

Finally, we analyze whether the daily returns of the companies are correlated. A PairGrid is used to visualize the relationships between the percentage changes in daily stock prices, followed by calculating the correlation matrix for daily returns.

#### PairGrid of Daily Returns
![PairGrid](https://github.com/user-attachments/assets/d3d1a675-7025-4f8d-a590-c0181c23469c)

#### Correlation Matrix of Daily Returns
![Correlation Matrix](https://github.com/user-attachments/assets/65e718c8-19c6-4ce6-a239-591eeec2e01c)

## Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib** & **Seaborn**: Data visualization
- **Plotly**: Interactive graphing library
- **Jupyter Notebook**: For interactive computing

## About Me

Hello, I'm Akhilesh Thapliyal!

## Contact
- **Email:** akhilesh.thedev@gmail.com
- **LinkedIn:** www.linkedin.com/in/akhilesh-thapliyal
- **GitHub:** https://github.com/The-Akhilesh-Thapliyal
