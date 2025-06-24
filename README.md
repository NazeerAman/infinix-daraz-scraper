# 📱 Infinix Daraz Scraper

This project is a simple Python-based web scraper that collects **Infinix phone model names, prices, and product links** from [Daraz.pk](https://www.daraz.pk/). It uses **Selenium** and **BeautifulSoup** for browser automation and HTML parsing.

## 📌 Project Overview

The script scrapes multiple pages from Daraz's search results for the term "Infinix" and organizes the extracted data into a structured dictionary. This is useful for market research, price comparison, or monitoring e-commerce product listings.

## 🔍 Features

- Extracts:
  - Model names
  - Prices in PKR
  - Product (Buy Now) links
- Works across multiple pages
- Saves data in Python dictionary format

## 🖼️ Example Output

```python
{
  "Models": ["Infinix Hot 12", "Infinix Zero X Pro", ...],
  "Prices(Rs)": ["29,999", "45,999", ...],
  "Buy Now": ["https://www.daraz.pk/...", ...]
}
```

## ⚙️ Requirements

Install dependencies using:

```bash
pip install beautifulsoup4 selenium pandas
```


## 🧠 How It Works

1. Open the notebook `infinix_daraz_scraper.ipynb`
2. Run each cell in order
3. The scraper:
   - Opens Daraz search results for “Infinix”
   - Parses each page's HTML using BeautifulSoup
   - Collects product information
   - Closes the browser automatically
4. The result is stored in a Python dictionary

## 📁 File Structure

```plaintext
.
├── infinix_daraz_scraper.ipynb   
├── README.md                   
├── requirements.txt              
├── first_page_infinix_phones.csv  \
└── infinix_phone_20Pages.csv
```

## 🧑‍💻 Author

**Nazeer Aman**  
GitHub: [@NazeerAman](https://github.com/NazeerAman)
