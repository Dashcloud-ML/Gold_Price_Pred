# Gold Price Prediction Web Application

## Overview
This project is a web application designed for a gold shop, featuring real-time gold and silver price displays and a gold price prediction model. Users can view current prices, place orders, and see predicted future prices based on historical data.

## Abstract

The Gold Price Prediction Web Application is designed to serve as an online platform for a gold shop, providing users with real-time updates on gold and silver prices alongside a predictive analytics feature. By leveraging historical pricing data, the application employs machine learning techniques to forecast future gold prices, helping customers make informed purchasing decisions. The platform also includes a basic online ordering system, allowing users to conveniently place orders. This project aims to enhance customer engagement and streamline the purchasing process, while serving as a valuable tool for price analysis in the gold market.


## Features
- **Real-Time Price Display**: Show current gold and silver prices.
- **Online Ordering**: Basic order form for customers to submit their orders.
- **Gold Price Prediction**: Predict future gold prices using historical data.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript (React)
- **Backend**: Node.js, Express
- **Database**: MongoDB (or any other database of your choice)
- **Machine Learning**: Python (scikit-learn or similar for the prediction model)

## Machine Learning Model
The price prediction model is built using:
- **Algorithm**: Linear Regression (initial version) / ARIMA (for time-series data)
- **Input Data**: Historical gold price data, optional financial indicators (inflation, currency rates)
- **Libraries**: scikit-learn, pandas, numpy
- **Deployment**: The model is deployed as a REST API using Flask, which is called by the React frontend for predictions.

## Gold Price Prediction Using Machine Learning
Historically, gold had been used as a form of currency in various parts of the world including USA. In present times, precious metals like gold are held with central banks of all countries to guarantee re-payment of foreign debts, and also to control inflation which results in reflecting the financial strength of the country.

Forecasting rise and fall in the daily gold rates, can help investors to decide when to buy (or sell) the commodity.

We in this project would forecast gold rates using the most comprehensive set of features and would apply various machine learning algorithms for forecasting and compare their results. We also identify the attributes that highly influence the gold rates.


![Alt text](https://github.com/Dashcloud-ML/Gold_Price_Pred/blob/main/Screenshot%202024-09-26%20233228.png)



