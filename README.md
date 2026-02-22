# P1-Project
# 📊 Stock Market Analysis 
# 📌 Overview

This project demonstrates an end-to-end ETL (Extract, Transform, Load) pipeline using Python.
It extracts stock market data, cleans and transforms it, stores it in a MySQL database, and generates analytical insights through visualizations.

This project showcases skills in data engineering, SQL integration, data cleaning, and financial analysis.

# 🚀 Features
# 🔹 Data Extraction

Loads stock datasets for multiple companies.

Merges datasets into a unified DataFrame.

# 🔹 Data Cleaning & Transformation

Converts date column to proper datetime format.

Handles missing values:

Missing volume → replaced with 0

Missing high/low → filled using logical rules

Removes duplicate records.

Ensures price consistency:

High ≥ Open/Close ≥ Low

Creates new calculated columns:

daily_return

return_category (Gain/Loss)

# 🔹 Data Loading (ETL Pipeline)

Connects Python to MySQL using SQLAlchemy.

Loads processed data into stock_prices table.

# 🔹 Data Analysis & Insights

📈 Daily closing price trends.

📉 Volatility analysis using standard deviation.

📊 Volume vs price movement correlation.

🔄 7-day & 30-day moving averages.

🏆 Best performing stock identification.

⚠️ Detection of abnormal trading volume spikes.

# 🛠️ Tech Stack

Programming: Python

Libraries: Pandas, NumPy, Matplotlib, SQLAlchemy, PyMySQL

Database: MySQL

Environment: Jupyter Notebook
