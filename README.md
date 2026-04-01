# Customer-Behavior-Dashboard-
Customer shopping behavior analysis using Python, SQL, and Power BI to uncover insights on spending patterns, customer segments, and product performance.
# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.
The objective is to uncover insights into customer spending patterns, product preferences, and subscription behavior to support better business decisions.

---

## 📊 Dataset Summary

* **Total Rows:** 3,900
* **Total Columns:** 18

### 🔑 Key Features:

* **Customer Demographics:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
* **Shopping Behavior:** Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

### ⚠️ Data Quality:

* Missing values found in **Review Rating** column (37 values)

---

## 🧹 Data Cleaning & Preparation (Python)

Performed using **Pandas**:

* Loaded dataset and explored structure using `.info()` and `.describe()`
* Handled missing values by imputing **median rating per category**
* Renamed columns to **snake_case** for consistency
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Removed redundant column: `promo_code_used`
* Loaded cleaned data into **PostgreSQL** for further analysis

---

## 🗄️ Data Analysis (SQL)

Used SQL to answer key business questions:

1. Revenue comparison by gender
2. High-spending customers using discounts
3. Top 5 products by average rating
4. Purchase behavior by shipping type
5. Subscriber vs non-subscriber revenue analysis
6. Discount-dependent products
7. Customer segmentation (New, Returning, Loyal)
8. Top 3 products per category
9. Relationship between repeat buyers and subscriptions
10. Revenue contribution by age group

---

## 📈 Dashboard (Power BI)

Created an interactive dashboard to visualize:

* Revenue trends
* Customer segments
* Product performance
* Subscription insights

---

## 💡 Business Recommendations

* 🚀 Promote subscription benefits to increase conversions
* 🎯 Implement customer loyalty programs
* 💰 Optimize discount strategies for profitability
* ⭐ Highlight top-rated products in marketing campaigns
* 📊 Focus marketing on high-value customer segments

---

## 🛠️ Tools & Technologies

* **Python (Pandas, NumPy)**
* **SQL (PostgreSQL)**
* **Power BI**
* **Excel**
Project Preview

![Dashboard Screenshot](https://github.com/AmrithaThampiS/Customer-Behavior-Dashboard-/blob/main/CUSTOMERDASHBOARD.png)


