# 📊 E-Commerce Sales Data Analysis

This repository contains an end-to-end exploratory data analysis (EDA) project performed on a real-world e-commerce dataset. The goal is to extract meaningful insights from transactional data to support business decisions in areas like marketing, customer behavior, sales performance, and product strategy.

---

## 🧠 Project Objective

The main objective of this project is to analyze e-commerce sales data and uncover hidden patterns that can:
- Improve customer acquisition and retention
- Evaluate product and category performance
- Understand regional sales distribution
- Analyze customer satisfaction through reviews
- Track and optimize payment methods

---

## 📁 Dataset Description

The dataset used is the **Brazilian E-Commerce Public Dataset by Olist**, available on [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). It includes the following CSV files:

- `customers.csv`
- `orders.csv`
- `order_items.csv`
- `order_payments.csv`
- `order_reviews.csv`
- `products.csv`
- `sellers.csv`
- `geolocation.csv`

Each file contributes to understanding different aspects of the e-commerce platform including customers, sellers, reviews, orders, and payments.

---

## 🧰 Tools & Technologies

- **Language:** Python 3.x
- **Environment:** Jupyter Notebook
- **Libraries Used:**
  - `pandas` – data manipulation
  - `numpy` – numerical operations
  - `matplotlib` & `seaborn` – visualizations
  - `plotly` – interactive plots
  - `datetime`, `itertools`, `collections` – date and data utilities

---

## 🧹 Data Preprocessing

- Removed null and duplicate values
- Standardized data types (e.g., datetime for timestamps)
- Filtered orders with status = 'delivered'
- Cleaned and merged relevant datasets

---

## 📊 Exploratory Data Analysis (EDA)

Key analytical areas:

1. **Customer Analysis**
   - Monthly new customer acquisition
   - Customer retention rates
   - Revenue from new vs returning users

2. **Sales & Product Trends**
   - Sales & quantity by product category and location
   - Top-selling products and cities

3. **Time-Based Trends**
   - Monthly, weekly, daily, and hourly sales analysis

4. **Payment Behavior**
   - Preferred payment methods and revenue trends

5. **Customer Satisfaction**
   - Product and category ratings
   - Regional satisfaction insights

6. **Advanced Insights**
   - Frequently bought together products
   - Top-rated & lowest-rated items
   - High-value vs high-volume categories

---

## 📌 Key Insights

- 📈 New customers are increasing month-over-month.
- 🤝 Retention is inconsistent – loyalty programs can help.
- 🛍️ Most revenue comes from repeat customers.
- 🌍 Cities like São Paulo and Rio generate maximum sales.
- ⏰ Sales peak during evenings and in festive months.
- 💳 Credit cards dominate high-value transactions.
- 💬 Customer feedback reveals areas needing improvement.

---

## 🚧 Challenges Faced

- Handling missing and inconsistent data
- Overcrowded visualizations with large categorical data
- Dealing with outliers and extreme values in transactions

---

## 🔮 Future Work

- Implement predictive models (e.g., churn prediction, sales forecasting)
- Build a recommendation system (frequently bought together)
- Create interactive BI dashboards using Power BI or Tableau
- Automate real-time reporting pipelines

---

## 🏁 Conclusion

This project demonstrates how data analysis can transform raw transactional data into actionable business intelligence. It empowers better decisions in marketing, inventory planning, customer service, and operational efficiency.

---

## 📎 References

- 📂 Dataset: [Brazilian E-Commerce Dataset - Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- 📘 Python Docs: [https://docs.python.org](https://docs.python.org)
