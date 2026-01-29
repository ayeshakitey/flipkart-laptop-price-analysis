# Laptop Price & Rating Analysis Using Web Scraping and EDA

## Overview

This project presents a **data-driven analysis of laptop prices and customer ratings** collected from the Flipkart e-commerce platform. The objective is to transform unstructured web data into actionable insights using **Python-based web scraping and exploratory data analysis (EDA)** techniques.

---

## Project Objectives

* Extract laptop data from an e-commerce website using web scraping
* Perform data cleaning and preprocessing on raw HTML data
* Conduct Exploratory Data Analysis to identify pricing and rating trends
* Analyze relationships between brand, price, and customer ratings
* Visualize insights to support business and consumer decision-making

---

## Data Source

* **Platform:** Flipkart
* **Category:** Laptops
* **Data Collection Method:** Pagination-based web scraping

---

## Tools & Technologies

* Python
* Requests
* BeautifulSoup
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Dataset Summary

| Feature     | Description         | Type        |
| ----------- | ------------------- | ----------- |
| Brand       | Laptop manufacturer | Categorical |
| Laptop_Name | Cleaned model name  | Categorical |
| Price       | Laptop price in INR | Numerical   |
| Rating      | Customer rating     | Numerical   |

* **Total Records:** ~240
* **File Format:** CSV

---

## Data Processing

* Removed irrelevant specifications from product names
* Standardized brand extraction
* Converted price to numeric format
* Handled missing and inconsistent rating values

---

## Exploratory Data Analysis

### Univariate Analysis

* Distribution of prices and ratings
* Brand-wise product count

### Bivariate & Multivariate Analysis

* Price vs Rating relationship
* Brand-wise average pricing
* Crosstab and pivot table analysis

---

## Key Findings

* Laptop pricing varies significantly by brand
* Customer ratings do not strongly correlate with price
* Several mid-range laptops receive high customer ratings
* Brand positioning plays a critical role in price determination

---

## Conclusion

This project demonstrates the practical application of **web scraping and exploratory data analysis** to extract meaningful insights from real-world e-commerce data. The findings can assist both consumers in making informed purchase decisions and businesses in understanding competitive pricing dynamics.

---

## Challenges & Learnings

* Managing pagination during scraping
* Cleaning highly unstructured product titles
* Aligning scraped features across multiple pages
* Gained hands-on experience with real-world data pipelines

---

## Author

**Ayesha Kitey**
🔗 LinkedIn: www.linkedin.com/in/ayesha-kitey-06336025

---

⭐ Feel free to explore, fork, or contribute to this repository.



