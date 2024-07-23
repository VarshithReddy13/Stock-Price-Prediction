# Stock Price Prediction using Deep Learning

This project utilizes a deep learning model, specifically Long Short-Term Memory (LSTM) networks, to predict the closing stock prices of a company. The model is trained on historical stock price data and aims to forecast future prices.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Installation](#installation)

## Overview

Stock price prediction is a challenging task due to the complex and non-linear nature of financial markets. In this project, we employ LSTM networks to capture the temporal dependencies and trends in stock price data to make accurate predictions.

## Dataset

The dataset used in this project consists of historical stock prices. The key features include:
- Date
- Open price
- High price
- Low price
- Close price
- Volume

## Model Architecture

The model architecture includes:
- Two LSTM layers with 50 hidden units each
- Two dense layers with 25 neurons and 1 neuron, respectively

The model is trained to minimize the root mean squared error (RMSE) between the predicted and actual closing prices.

## Results

The model effectively captured long-term dependencies and trends in the data by analyzing the past 60 days' closing prices of the stock, achieving a root mean squared error (RMSE) of 0.0485.

## Installation

To run this project, you need to have Python and the following libraries installed:

- numpy
- pandas
- matplotlib
- scikit-learn
- tensorflow

You can install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
