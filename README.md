# 🛍️ Customer Shopping Behavior Analysis

A complete end-to-end data analytics project that analyzes customer shopping behavior using **Python, SQL (PostgreSQL), and Power BI** to uncover insights into spending patterns, product performance, and customer loyalty.

---

## 📌 Project Objective

A retail company wants to better understand how customers shop across demographics, categories, and seasons.

**Business Question:**

> *How can the company use shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?*

---

## 📂 Dataset Overview

| Attribute | Value |
|----------|------|
| Records | 3,900 transactions |
| Columns | 18 |
| Key Fields | Age, Gender, Location, Category, Purchase Amount, Season, Discount Applied, Subscription Status, Review Rating |
| Missing Values | 37 missing in `Review Rating` |

---

## 🛠️ Tools & Technologies

- **Python** – pandas, numpy, sqlalchemy  
- **PostgreSQL** – Structured data analysis using SQL  
- **Power BI** – Interactive dashboard  
- **Jupyter Notebook** – Data preparation & EDA  

---

## 🔄 Workflow

### 1️⃣ Data Preparation (Python)

- Loaded and explored dataset using `pandas`
- Handled missing values in `Review Rating` using **category-wise median**
- Standardized column names to `snake_case`
- Created new features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant column `promo_code_used`
- Connected to **PostgreSQL** and pushed cleaned data using SQLAlchemy

---

### 2️⃣ Business Analysis (SQL)

| # | Analysis |
|---|---------|
| 1 | Revenue comparison by Gender |
| 2 | High-spending customers using discounts |
| 3 | Top 5 products by review rating |
| 4 | Standard vs Express shipping spend |
| 5 | Subscribers vs Non-Subscribers revenue |
| 6 | Products most dependent on discounts |
| 7 | Customer segmentation – New, Returning, Loyal |
| 8 | Top 3 products in each category |
| 9 | Subscription likelihood for repeat buyers |
|10 | Revenue contribution by Age Group |

---

### 3️⃣ Visualization (Power BI)

An interactive dashboard displaying:

- Revenue trends  
- Customer segmentation  
- Product performance  
- Subscription behavior  
- Shipping & discount analysis  

---

## 📊 Business Recommendations

- 🎯 **Boost Subscriptions** – Promote premium benefits  
- 🏆 **Customer Loyalty Programs** – Reward repeat buyers  
- 💸 **Review Discount Strategy** – Protect profit margins  
- 📈 **Product Promotion** – Highlight best-rated products  
- 🧠 **Targeted Marketing** – Focus on high-value age groups  

---

## 📁 Repository Structure

📦 Customer-Shopping-Behavior-Analysis<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- 📂 data<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- 📂 notebook<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- 📂 sql_queries<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- 📂 powerbi_dashboard<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- 📜 README.md


---

## 🚀 How to Run the Project

1. Run Python notebook for data cleaning  
2. Load cleaned data into PostgreSQL  
3. Execute SQL queries  
4. Open the Power BI file to explore the dashboard  

---

## 🙌 Conclusion

This project demonstrates how raw transactional data can be transformed into meaningful business insights using Python, SQL, and Power BI.
