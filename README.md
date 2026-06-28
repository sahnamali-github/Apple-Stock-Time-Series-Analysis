# 📈 Apple Stock Price Time Series Analysis

A data analysis project that explores historical stock price trends of **Apple Inc. (AAPL)** using **Python**, **Yahoo Finance**, **Pandas**, and **Plotly**. The project retrieves historical market data, performs exploratory analysis, and visualizes stock price movements through an interactive time series chart.

---

## 📌 Overview

Financial time series analysis helps identify market trends and understand how stock prices change over time. This project demonstrates how historical stock market data can be collected programmatically and visualized to explore price movements.

Using the **Yahoo Finance API**, the project downloads approximately two years of Apple stock data and creates an interactive line chart of daily closing prices.

---

## 🚀 Features

* 📥 Retrieve historical stock market data
* 📅 Automatically select a two-year date range
* 📊 Explore historical stock price data
* 📈 Interactive time series visualization
* 🐍 Data analysis using Pandas
* ⚡ Real-time data retrieval with Yahoo Finance

---

## 📂 Dataset

Instead of using a static dataset, this project fetches historical stock market data directly from **Yahoo Finance** using the `yfinance` library.

Retrieved attributes include:

| Column    | Description                          |
| --------- | ------------------------------------ |
| Open      | Opening stock price                  |
| High      | Highest price during the trading day |
| Low       | Lowest price during the trading day  |
| Close     | Closing stock price                  |
| Adj Close | Adjusted closing price               |
| Volume    | Number of shares traded              |

---

## 🛠️ Technologies Used

* Python
* Pandas
* yfinance
* Plotly

---

## 🔄 Project Workflow

### 1. Retrieve Historical Data

The project automatically calculates a two-year date range and downloads Apple's historical stock data using the Yahoo Finance API.

---

### 2. Explore the Dataset

The downloaded data is inspected using:

* First few records
* Dataset structure
* Historical market values

---

### 3. Visualize Stock Prices

An interactive Plotly line chart is created using the daily closing prices, allowing users to observe trends and fluctuations over time.

---

## 📊 Output

The project generates:

* 📈 Interactive Time Series Line Chart
* 📋 Historical Stock Market Dataset
* 📊 Daily Closing Price Trend

---

## 📁 Project Structure

```text
Apple-Stock-Time-Series-Analysis/
│
├── stock_analysis.ipynb
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Apple-Stock-Time-Series-Analysis.git
```

Navigate to the project directory:

```bash
cd Apple-Stock-Time-Series-Analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook or Python script.

---

## 📦 Required Libraries

```text
pandas
yfinance
plotly
```

Or install them manually:

```bash
pip install pandas yfinance plotly
```

---

## 📈 Sample Analysis

The interactive line chart visualizes Apple's daily closing prices over approximately two years, making it easy to observe long-term trends, market fluctuations, and periods of growth or decline.

---

## 📚 Learning Outcomes

Through this project, I explored:

* Financial time series analysis
* Working with financial APIs
* Data retrieval using yfinance
* Data manipulation using Pandas
* Interactive visualization using Plotly
* Time series visualization techniques

---

## 🔮 Future Improvements

* Compare multiple stocks in a single visualization
* Add moving averages (SMA and EMA)
* Visualize trading volume trends
* Calculate daily returns and volatility
* Forecast future prices using machine learning or statistical models
* Build an interactive dashboard using Streamlit

---

## 🎓 About This Project

This project was developed as part of my learning journey in data analysis and financial data visualization using Python. It demonstrates how historical stock market data can be collected, analyzed, and visualized through interactive time series charts to better understand price trends.
