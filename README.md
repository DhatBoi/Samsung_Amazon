# 📘 samsung_Amazon.ipynb

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

A Python script using BeautifulSoup, requests, pandas, and numpy to scrape Amazon product listings for Samsung phones.  It extracts key details and outputs them to a structured CSV file for analysis.

# Amazon Product Scraper for Samsung Phones

This Jupyter Notebook (`samsung_Amazon.ipynb`) scrapes product information from Amazon search results for "Samsung phones".  It extracts details such as product title, price, rating, review count, and availability and saves the data to a CSV file.

##  Dependencies

* **BeautifulSoup4:** For parsing HTML content.
* **requests:** For making HTTP requests to fetch web pages.
* **pandas:** For creating and manipulating DataFrames.
* **numpy:** For handling NaN values in the dataframe.

You can install these libraries using pip:

```bash
pip install beautifulsoup4 requests pandas numpy
