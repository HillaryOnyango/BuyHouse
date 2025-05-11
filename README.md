# BuyHouse
# Web Scraping and Data Analysis with Python

This project demonstrates how to perform basic web scraping and data analysis using Python libraries such as `requests`, `BeautifulSoup`, and `pandas`. The data is stored in a Postgres SQL database using SQLAlchemy. The base URL for the project is 'https://www.buyrentkenya.com/houses-for-sale' from the website "BuyRentKenya"

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
**PoweBI,Cleaning and Visualization**
Once the data is stored in the PostgreSQL db, which is connected using DBeaver(for) localhost, the data is then accessed using PowerBI for after cleaning the final phase is visualizaton. 
