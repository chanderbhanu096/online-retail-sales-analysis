# 🛍️ E-Commerce Sales Analysis

**Author:** Chander Bhanu
**Date:** August 2025  

---

## 📌 Project Overview
This project analyzes an e-commerce transactional dataset to uncover insights into sales performance, customer behavior, and product demand.  
The dataset contains individual transactions, including product details, customer IDs, and transaction timestamps.

---

## 📂 Files in Repository
- **`ecommerce_data.csv`** → Raw dataset used for analysis  
- **`ecommerce_analysis.ipynb`** → Jupyter Notebook with data cleaning, exploration, and insights  
- **`README.md`** → This file, describing the project  

---

## 🔍 Project Workflow
1. **Data Import & Initial Exploration**  
   - Load CSV dataset into Pandas  
   - Check dataset structure and missing values  

2. **Data Cleaning**  
   - Remove transactions with negative/zero quantities  
   - Drop rows with missing `CustomerID`  
   - Calculate `Revenue` as `Quantity × UnitPrice`  

3. **Exploratory Data Analysis (EDA)**  
   - Identify top customers by revenue  
   - Find top-selling products  
   - Analyze sales by country  
   - Visualize daily revenue trends  

4. **Key Insights**  
   - A small number of customers and products generate most of the revenue  
   - Seasonal sales trends suggest strong Q4 performance  
   - High-value customer segments can be targeted for retention campaigns  

---

## 🛠 Tools & Libraries
- **Python (3.x)**  
- **Pandas** — Data manipulation  
- **Matplotlib** — Data visualization  
- **Seaborn** — Statistical visualizations  

---

## ▶ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
