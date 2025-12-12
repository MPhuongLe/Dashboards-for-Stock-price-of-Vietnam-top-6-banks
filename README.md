# Dashboards for Stock Prices of Vietnam's Top 6 Banks

## 📌 Overview

This project is part of our Time-Series Data Analysis lab, focusing on real-world stock market data.

After analyzing and visualizing the stock prices of the top six banks in Vietnam (see our [previous project](https://github.com/MPhuongLe/Stock-price-Analysis-and-Visualization-of-Vietnam-top-6-banks)), we extend the work by learning how to deliver insights through **interactive dashboards** built with:

- **Tableau**
- **Streamlit**

> We also explored **Power BI** in a related project. If you're interested, check out  
> the [Analysis of Covid-19 Pandemic in Vietnam](https://github.com/MPhuongLe/Analysis-of-Covid-19-Pandemic-in-Vietnam).

---

## 🎯 Objectives

- Provide an overview of the stock performance of the six banks with the highest brand value in Vietnam  
- Offer tools to monitor price and trading volume fluctuations  
- Forecast future stock prices using an **LSTM** model  

---

## 🎯 Target

### Visualization Targets  
The dashboards visualize the stock data of six banks ranked highest in brand value according to the [Brand Finance Banking 500 Report](https://static.branddirectory.com/reports/brand-finance-banking-500-2023-preview.pdf): **Vietcombank, Agribank, BIDV, Techcombank, VietinBank, VPBank**.

### Intended Users  
These dashboards are designed for:

- Individuals interested in the stock market and the performance of Vietnam’s top banks  
- Users with a basic understanding of stock trading concepts such as:  
  opening/closing prices, high/low prices, trading volume, and moving averages  

---

## 📁 Dataset

For details regarding the data source and preprocessing steps, please refer to our  
[previous project](https://github.com/MPhuongLe/Stock-price-Analysis-and-Visualization-of-Vietnam-top-6-banks).

---

## 📊 Dashboards

We use **two dashboarding tools**, each chosen for its unique strengths.

---

### **1. Power BI — Main Dashboard Suite**

The Power BI suite contains **three component dashboards**:

#### 📌 *Tracking Dashboard*  
Provides tools to monitor stock price movements and trading volume for each bank.

#### 📌 *Overview Dashboard*  
Offers a high-level comparison of all six banks, including rankings, prices, and trading volumes.

#### 📌 *Prediction Dashboard*  
Forecasts each bank’s stock price using the **LSTM** model.

---

### **2. Plotly Dash — Extended Dashboard**

This interactive dashboard includes **three functional tabs**:

#### 📌 *Trading Signals*  
Displays trading signals derived from different moving average configurations.

#### 📌 *Predict Stock Price*  
Generates stock price forecasts using the **LSTM** model.

#### 📌 *Comparison Between Stocks*  
Allows users to compare highest/lowest prices and trading volumes across multiple banks.

All source code for both Plotly Dash and Power BI dashboards is available in the `dashboards/` directory.

---

## 📑 Analysis

- Detailed analysis is included in **`report.pdf`**.  
- A demonstration video showcasing the dashboards and insights (in Vietnamese) is available here:  
  👉 https://www.youtube.com/watch?v=ai__PgfKgQg

---

## 👥 Team Members

This project was collaboratively developed by:

- **Lê Công Đắt**  
- **Lê Trần Minh Khuê**  
- **Hoàng Trung Nam**  
- **Lê Trần Như Ngọc**  
- **Lê Thị Minh Phương** (Repository Owner & Team Lead)

Guided by: **Ms. Lê Nhựt Nam**  
Course: **Data Visualization – University of Science, VNU-HCM**

---
