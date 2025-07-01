# 🚀 Web Scraping Challenge – Mission to Mars

## 🪐 Overview

Welcome to your first full-scale **web scraping and data analysis** mission!

This project is divided into two deliverables:

1. **Scrape the latest Mars news headlines** from a live webpage using **Splinter** and **Beautiful Soup**.
2. **Scrape and analyze Mars weather data**, stored in an HTML table, using **Beautiful Soup**, **Pandas**, and **Matplotlib**.

This challenge focuses on real-world skills in automated web browsing, HTML parsing, data transformation, and insight generation through visualizations.
---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Splinter (browser automation)
- Beautiful Soup (HTML parsing)
- Pandas
- Matplotlib
- WebDriver Manager

---

## 🌕 Part 1: Mars News Scraper

### ✅ Objective

Scrape the **title** and **preview** text for the latest articles on [Red Planet Science](https://static.bc-edx.com/data/web/mars_news/index.html).

### 🔍 Process

- Automated browsing via Splinter to access the news site
- Parsing HTML using Beautiful Soup
- Extraction of `<div class="content_title">` and `<div class="article_teaser_body">` elements
- Storing each article in a dictionary:
```python
{'title': 'NASA Launches New Mars Lander', 'preview': 'A new era of Mars exploration begins...'}
- Exporting all results as a list of dictionaries
-	Optional: saving the data to a mars_news.json file

## 🌡️ Part 2: Mars Weather Analysis

### ✅ Objective

Scrape weather data from Mars Weather Table and analyze:
	•	Martian temperatures
	•	Atmospheric pressure
	•	Seasonal patterns

🔍 Process
	•	Used Splinter and Beautiful Soup to extract table data
	•	Stored data in a Pandas DataFrame with proper column names:
	•	id, terrestrial_date, sol, ls, month, min_temp, pressure
	•	Converted column data types appropriately

# 📊 Analysis Performed
	1.	How many months exist on Mars?
➤ Found using unique values in the month column.
	2.	How many Martian days of data exist?
➤ Total number of unique sols in dataset.
	3.	Coldest & Warmest Months on Mars
➤ Grouped by month, calculated average min_temp, visualized with a bar chart.
	4.	Highest & Lowest Atmospheric Pressure
➤ Grouped by month, averaged pressure, visualized with a bar chart.
	5.	Martian Year Length (in Earth days)
➤ Plotted daily minimum temperatures to estimate when seasons repeat.

# 📤 Output
	•	Cleaned data exported to: mars_weather_data.csv

🧑‍💻 Author

Aditi Nankar
Data Analytics | Web Scraping | Visualization
