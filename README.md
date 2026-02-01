# Cryptocurrency_Price_Tracker
Cryptocurrency_Price_Tracker

### 📊 Cryptocurrency Price Tracker & Market Analysis System

A Python-based real-time cryptocurrency tracking application that scrapes live market data from CoinMarketCap, stores historical prices, and analyzes top-performing cryptocurrencies using automation and data analysis techniques.

## I. Overview

The Cryptocurrency Price Tracker is designed to fetch and analyze real-time cryptocurrency market data.
It uses Selenium automation to scrape dynamically loaded content from CoinMarketCap, processes the data using Pandas, and stores it in CSV format for historical tracking and analysis.
This project demonstrates web automation, data collection, and basic financial market analysis.

## II. Project Modules

This project is divided into 6 major modules:

# 1. Browser Automation Module

Launches headless Chrome browser
Opens CoinMarketCap dynamically using Selenium
Handles page load and timeout conditions

# 2. Data Extraction Module

Scrapes Top 10 cryptocurrencies
Extracts:

Rank
Name
Price
24h Change
Market Capitalization

# 3. Timestamping Module

Records real-time timestamp for each fetch
Enables historical tracking of prices

# 4. Data Storage Module

Saves extracted data into CSV format
Appends new records for continuous tracking

# 5. Data Analysis Module

Identifies top gainers based on 24-hour percentage change
Filters coins gaining more than +5%

# 6. Reporting Module

Displays latest crypto data in tabular format
Shows gainers summary in the terminal

### III. Technologies Used
# Backend & Core
Python 🐍
Pandas
Selenium
WebDriver Manager

# Automation
Chrome WebDriver
Headless browser execution

# Data Handling
CSV file storage
Time-based data logging

### IV. Features
1️⃣ Real-Time Cryptocurrency Tracking

Fetches live prices from CoinMarketCap
Works on dynamically loaded web pages

2️⃣ Automated Web Scraping

Uses Selenium for JavaScript-rendered content
Headless execution for fast performance

3️⃣ Market Analysis

Detects top 24h gainers
Easy-to-read market insights

4️⃣ Historical Data Storage

Automatically saves data to CSV
Supports long-term trend analysis

5️⃣ Scalable Design

# .Easy to extend for:

Alerts
Dashboards
Advanced analytics

### V. How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/Cryptocurrency_Price_Tracker.git
cd Cryptocurrency_Price_Tracker

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Program
python crypto_browser.py

### VI. Output

Displays live cryptocurrency data in the terminal
Saves data automatically to:
data/crypto_prices.csv

### VII. Testing

Tested with multiple runs for consistency
Verified dynamic page scraping reliability
CSV data integrity validation

### VIII. Future Enhancements

Deploy as a web dashboard using Streamlit
Replace Selenium with Crypto APIs
Add real-time price alerts
Visualize trends using Matplotlib / Plotly
Schedule automatic execution using Task Scheduler

# 📜 License

This project is licensed under the MIT License — free for academic and personal use.

# 🤝 Contributing

Contributions, issues, and feature requests are welcome.
Feel free to fork the repository and submit a pull request.

# ⭐ Acknowledgements

CoinMarketCap for market data
Selenium community
Open-source Python ecosystem
