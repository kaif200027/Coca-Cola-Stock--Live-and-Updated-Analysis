# Coca-Cola-Stock--Live-and-Updated-Analysis
Coca Cola Stock- Live and Updated Analysis
Coca-Cola Stock Analysis - Live and Updated
Project Overview
This project is dedicated to analyzing the historical stock data of The Coca-Cola Company to uncover market trends and predict future stock prices. Utilizing a combination of data analytics and visualization techniques in Python, the project performs Exploratory Data Analysis (EDA), generates technical indicators, and applies a Random Forest model for robust stock price prediction. A key feature of this project is the development of a basic live prediction system that forecasts Coca-Cola's closing price using real-time data from Yahoo Finance.

Objective
To analyze historical stock price movements and trends of The Coca-Cola Company.

To generate and visualize key technical indicators to understand market dynamics.

To build a predictive model (Random Forest) for forecasting Coca-Cola's stock prices.

To implement a live prediction system using real-time data for practical application.

Dataset Description
The analysis is based on historical stock data with the following features:

Date: The trading date of the stock (in YYYY-MM-DD format).

Open: The price at which the stock opened on that particular day.

High: The highest price of the stock during the trading session.

Low: The lowest price of the stock during the trading session.

Close: The final price of the stock when the market closed.

Volume: The total number of shares traded on that day.

Dividends: Cash paid to shareholders per share (if any) on that date.

Stock Splits: Indicates any stock splits that occurred (e.g., 2-for-1 split = 2).

Analysis and Key Insights
The project includes several analyses and visualizations, providing the following insights:

Coca-Cola Close Price with Moving Averages: A line chart displays Coca-Cola's closing stock prices over time, along with 20-day and 50-day moving averages. These moving averages help in identifying short-term and mid-term price trends and smoothing out daily fluctuations.

Correlation Heatmap: A correlation heatmap illustrates the relationships between various financial indicators such as Open, High, Low, Close, Volume, Daily Return, and Volatility. This helps in understanding how different metrics move in relation to each other.

Daily Return Distribution: A histogram visualizes the daily return distribution of Coca-Cola, showing the frequency of different daily return values. Most returns are clustered around zero, indicating that significant daily price swings are less common.

Simple Forecast using 7-day Moving Average: A graph illustrates a simple forecast of Coca-Cola's price using a 7-day Moving Average. It compares the forecasted price (orange dashed line) against the actual price (blue solid line) over a specific period, demonstrating the basic predictive capability.

Technologies Used
Python

Pandas (for data manipulation)

Matplotlib / Seaborn (for data visualization)

Scikit-learn (for Random Forest model)

Yahoo Finance API (for real-time data)

How to Run (Assumed
