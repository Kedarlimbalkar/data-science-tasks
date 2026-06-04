# Globussoft Data Science Assignment — Task 1

## Amazon.in Laptop Scraper

A Python script that scrapes laptop product listings from Amazon.in and saves the data into a CSV file with a timestamp in the filename.

---

## Fields Collected
- Title — Full product name
- Price (INR) — Price in Indian Rupees
- Rating — Star rating out of 5
- Image URL — Direct link to product image
- Result Type — Whether the listing is an Ad or Organic result

---

## Libraries Used
- requests — Send HTTP requests to Amazon
- beautifulsoup4 — Parse HTML and extract product data
- pandas — Store and export data to CSV
- fake_useragent — Rotate browser headers to avoid blocking

---

## How to Run
1. Open task1_amazon_scraper.ipynb in Jupyter Notebook or Google Colab
2. Run all cells top to bottom
3. Output CSV will be saved as amazon_laptops_YYYYMMDD_HHMMSS.csv

---

## Output Example
amazon_laptops_20260603_142530.csv

---

## Author
Kedar Limbalkar
GitHub: https://github.com/Kedarlimbalkar
