
# 🛒 E-commerce Review Scraper

A Python-based project to extract customer reviews from e-commerce product pages using web scraping techniques.

---

## 📌 Project Description

This project scrapes product review data from an e-commerce website and organizes it into a structured format using Python. It is designed to automate the process of collecting user feedback for further analysis.

---

## 🔍 Features

* Scrapes product reviews from e-commerce sites
* Extracts:

  * Reviewer name
  * Review title
  * Review content
  * Rating
  * Review date
* Stores reviews in a `pandas` DataFrame
* Optionally exports data to CSV

---

## 🧱 Workflow Summary

1. Send an HTTP request to the product review page
2. Parse the HTML using `BeautifulSoup`
3. Loop through review blocks and extract fields
4. Store the data in a DataFrame
5. (Optional) Export data to a `.csv` file

---

## 🧰 Tools & Libraries Used

* `requests` – to fetch HTML content
* `BeautifulSoup` – for parsing and navigating HTML
* `pandas` – to organize and manipulate the scraped data

---

## 📌 Output Example

A sample of the final data table:

| Reviewer     | Rating | Title     | Review Text               | Date      |
| ------------ | ------ | --------- | ------------------------- | --------- |
| Priya Sharma | 4.0    | Worth it! | Loved the product quality | July 2024 |

