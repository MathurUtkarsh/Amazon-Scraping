# Amazon Scraping

This code is an implementation of web scraping using BeautifulSoup library in Python to scrape product data from the given Amazon URL:
https://www.amazon.in/s?k=bags&crid=2M096C61O4MLT&qid=1653308124&sprefix=ba%2Caps%2C283&ref=sr_pg_1

The goal is to scrape at least 20 pages of product listing pages and extract the following information:

• Product URL

• Product Name

• Product Price

• Rating

• Number of reviews

The extracted data is stored in a list of dictionaries, where each dictionary corresponds to a product and its information.

In the next step, the code hits each of the product URLs in the list and extracts additional information:

• Description

• ASIN

• Product Description

• Manufacturer

Finally, the entire data is exported to a csv file "bags.csv" using the csv library in Python.

