# BuyHouse
# Web Scraping and Data Analysis with Python

This project demonstrates how to perform basic web scraping and data analysis using Python libraries such as `requests`, `BeautifulSoup`, and `pandas`. The data can optionally be stored in an SQL database using SQLAlchemy.

## 📁 Project Files

- `scraper.ipynb` – A Jupyter Notebook that performs the following tasks:
  - Sends an HTTP request to a website.
  - Parses the HTML content using BeautifulSoup.
  - Extracts specific elements from the page.
  - Stores the data in a pandas DataFrame.
  - Optionally saves the data to a local SQLite database using SQLAlchemy.

## 🛠️ Requirements

Install dependencies using pip:

```bash
pip install requests pandas beautifulsoup4 sqlalchemy lxml
