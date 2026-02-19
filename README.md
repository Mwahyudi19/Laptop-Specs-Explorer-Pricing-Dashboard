# 💻 E-Commerce Laptop Pricing & Specifications Dashboard

This project analyzes a dataset of e-commerce laptop products to uncover pricing strategies, hardware trends, and brand market share using **Python (Pandas)** for robust data preprocessing and **Microsoft Power BI** for interactive visualization.

## 🎯 What I Did (Executive Summary)
To complete this end-to-end analysis, I performed the following steps:
1. **Data Cleaning & Extraction (Python):** Used Pandas and complex Regex to clean dirty text data and extract hidden hardware specs (RAM, SSD, Core Processors) from messy product titles.
2. **Data Modeling (Power BI):** Built a structured data model and created custom DAX measures for accurate pricing and discount calculations.
3. **Data Visualization (Power BI):** Designed an interactive dashboard to analyze brand market share, hardware trends, and discount strategies.


## 🚀 Project Overview

The goal is to transform messy, unstructured text data into a clean, interactive dashboard to support strategic decision-making in competitive pricing and hardware market analysis. The analysis focuses on:

- **Market Share & Brand Dominance:** Analyzing the distribution of laptop models across top brands (e.g., HP, Lenovo, Apple, ASUS, Dell).
- **Hardware Specifications Trends:** Extracting and mapping the popularity of key components, specifically **RAM, SSD Capacity, and Core Processors**.
- **Pricing & Discount Strategies:** Evaluating average prices across brands and identifying which brands offer the highest **Saving (%)** to attract consumers.

## 📊 Dataset Description

The raw dataset (`priceoye_laptops_version_2.csv`) was cleaned and transformed into the master dataset (`priceoye_laptops_ready_to_analyze.csv`) containing over **300 records** with the following key attributes:
- **Product Info:** Brand, Cleaned Name, Cleaned Model Series.
- **Hardware Specs:** Core Processor (e.g., Core i5, Ryzen 7, M1), RAM (GB), SSD Storage.
- **Pricing Data:** Actual Price, Discounted Price, Saving Percentage (%).
- **Consumer Data:** User Ratings, Review Counts.

## 🛠️ Tools & Workflow

The entire analysis workflow was conducted using **Python** for Data Engineering and **Microsoft Power BI** for visual analytics:

1.  **Data Transformation & Feature Engineering (Python/Pandas):**
    - Handled missing values (imputation for ratings, reviews, and missing prices).
    - Utilized **Regular Expressions (Regex)** to extract hidden RAM, SSD, and Core processor data from messy product titles.
    - Standardized text formatting (Uppercase, removing noise, resolving edge cases like `8-512GB`) and labeled missing specs as `Unknown`.
    - Exported a 100% clean, analysis-ready CSV file.
  
## 📈 Key Insights

- **Hardware Standardization:** Despite the global shift toward higher capacities, **8GB RAM** remains the most supplied configuration in this marketplace (114 models), closely followed by **16GB RAM** (93 models). For processors, **Intel Core i7 and Core i5** dominate the landscape, significantly outpacing AMD Ryzen alternatives.
- **Discount Strategies & Market Capture:** Brands targeting the budget-to-mid segment employ aggressive promotional tactics. **Dell** and **HP** offer the highest average discounts (ranging from 15% to 16% OFF) to win price-sensitive consumers.
- **Brand Dominance & Price Positioning:** **HP and Lenovo** monopolize product volume, accounting for over 60% of all available models. Conversely, **Apple** maintains strict premium positioning, recording the highest average price with minimal promotional discounts compared to Windows-based competitors.

## 📷 Dashboard Preview
<img width="1409" height="794" alt="DASHBOARD" src="https://github.com/user-attachments/assets/e954576b-505e-497f-a451-1a8286ec4ed7" />

## 📂 File Contents
- <a href="https://github.com/Mwahyudi19/Laptop-Specs-Explorer-Pricing-Dashboard/blob/main/priceoye_laptops_version_2.csv">Raw Dataset (CSV)</a>
- <a href="https://github.com/Mwahyudi19/Laptop-Specs-Explorer-Pricing-Dashboard/blob/main/priceoye_laptops_ready_to_analyze.csv">Cleaned Dataset (CSV)</a> 
- <a href="https://github.com/Mwahyudi19/Laptop-Specs-Explorer-Pricing-Dashboard/blob/main/priceoye_laptops_clean_build.ipynb">Data Cleaning Script (Jupyter Notebook)</a>
- <a href="https://github.com/Mwahyudi19/Laptop-Specs-Explorer-Pricing-Dashboard/blob/main/Dashboard.pbix">Power BI Dashboard (.pbix)</a>
