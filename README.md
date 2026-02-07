# WebScrapingStockData
A Python project to scrape stock prices and financial data from **Meroshare** and store selected information in a PostgreSQL database. Built using **Beautiful Soup** and **requests**, this project demonstrates web scraping, data cleaning, and database integration.

---

## Features

- Scrapes stock data from Meroshare using stock symbols.  
- Extracts key financial information:
  - Market Price  
  - Percentage Change  
  - 52-Week High/Low  
- Cleans messy web-scraped data (removes whitespace, line breaks).  
- Inserts cleaned data into a PostgreSQL table for storage and querying.  
- Demonstrates basic CRUD operations: insert, fetch, delete.  

---

## Tech Stack

- Python 3.x  
- **Beautiful Soup 4** (`bs4`)  
- **Requests** for HTTP calls  
- **psycopg2** for PostgreSQL integration  
- **python-dotenv** for environment variable management  

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/WebScrapingStockData.git
cd WebScrapingStockData
