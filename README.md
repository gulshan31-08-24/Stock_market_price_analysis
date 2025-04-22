# 📈 stockPriceAnalysis

A data-driven project for analyzing historical stock prices, identifying trends, and visualizing market behavior using **Python**, **Apache Spark**, and other modern data science tools.

---

## 🚀 Project Overview

This project performs in-depth analysis of historical stock price data. It includes:

- 📥 Data collection from CSV files
- 🧹 Data preprocessing and cleaning
- 📊 Visualization of price movements
- 📈 Statistical and trend analysis using Apache Spark

The goal is to uncover meaningful patterns and trends in the financial markets.

---

## 🛠️ Technology Used

- ⚡ **Apache Spark** – for distributed stock price analysis  
- 📓 **Google Colab Notebook** – for writing and executing code in the cloud  
- 🐍 **Python** – data manipulation and visualization

---

## 🗃️ Dataset Used

**Folder Name:** `StockData`

The dataset contains multiple CSV files with historical stock data for various publicly traded companies like AAPL,AMZN etc.

---

## 📑 Dataset Description

Each CSV file contains data for a specific stock. The columns are:

| Column       | Description                                             |
|--------------|---------------------------------------------------------|
| `Ticker`     | Stock symbol (e.g., AAPL for Apple Inc.)               |
| `Date`       | The trading date (`MM/DD/YYYY`)                         |
| `Close/Last` | Closing price of the stock on that date (`$` prefixed) |
| `Volume`     | Number of shares traded                                 |
| `Open`       | Opening price on that date                              |
| `High`       | Highest price of the day                                |
| `Low`        | Lowest price of the day                                 |

### 📝 Sample Entry
Ticker: AAPL
Date: 05/31/2023
Close/Last: $177.25
Volume: 99,625,290
Open: $177.33
High: $179.35
Low: $176.76



