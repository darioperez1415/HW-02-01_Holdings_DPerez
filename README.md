# HW-02-01_Holdings_DPerez
ETF Investment Holdings Web Scraper
This project is a web scraping exercise that extracts investment holdings from various exchange-traded funds (ETFs) and organizes the data into a structured pandas DataFrame. The goal is to scrape ticker symbols (e.g., AAPL, NVDA) and their allocation weights, then format the data as floating-point values by removing percentage symbols.

Features
- ✅ Web scrape ETF holdings from publicly available sources
- ✅ Convert extracted data into a structured pandas DataFrame
- ✅ Ensure all allocation weights are in float format for further analysis

Example DataFrame Structure
AAPL	NVDA	MSFT	AMZN	AVGO	META	TSLA
QQQ	8.47	8.68	8.02	6.11	4.67	3.38	3.87

Data Source
A sample ETF holdings webpage: QQQ Holdings
(Note: This website displays only the top 50 holdings per ETF.)

Technologies Used
Python 🐍
pandas for data manipulation
BeautifulSoup / requests for web scraping
How to Use

Choose an ETF holdings webpage as your data source.
Run the script to scrape the ticker symbols and weights.
Convert the extracted data into a pandas DataFrame.
Use the cleaned dataset for financial analysis or visualization.
