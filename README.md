# 📊 Zomato Bangalore Restaurants — Exploratory Data Analysis (EDA)

## Overview

This project dives deep into the Zomato Bangalore restaurant dataset to uncover insights about the city's vibrant food scene. Through this EDA, I explored user preferences, cost distributions, cuisine trends, and more, using Python libraries like Pandas, Seaborn, and Matplotlib.

This analysis helps in understanding customer behavior, identifying features that contribute to higher ratings, and preparing the data for potential machine learning applications.

---

## 🔍 Key Insights & Highlights

- **Rating Trends**: Restaurants with the `dish_liked` feature tend to have significantly higher average ratings (3.9 vs. 3.4). This suggests positive customer feedback correlates with better ratings.
  
- **Cuisine Popularity**: The most common cuisines in Bangalore are:
  - North Indian
  - Chinese
  - South Indian
  - Fast Food
  - Biryani

- **Online Ordering Behavior**:
  - ~60% of restaurants offer online ordering.
  - Interestingly, the more expensive the restaurant, the less likely it is to support online orders.
  - High-cost restaurants tend to receive better ratings overall.

- **Cost Patterns**:
  - Most restaurants charge between ₹300–₹600 for two people.
  - A detailed distribution analysis helped identify outliers and standardize cost values.

- **Data Cleaning Steps**:
  - Cleaned up columns with string formatting issues (`approx_cost` with commas).
  - Replaced placeholder strings like `"NEW"` or `"-"` in rating columns with NaN.
  - Identified columns that could be dropped or used for NLP tasks (`menu_item`, `dish_liked`, etc.).

---

## 🧠 What I Learned

- Real-world datasets often require thoughtful cleaning and feature engineering.
- Visualizing data distributions is essential before making any modeling decisions.
- Customer sentiment (via features like `dish_liked`) can be a strong indicator of restaurant quality.

---

## 🛠️ Tools Used

- **Python**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**
- **Jupyter Notebook**
- **Kaggle API (for dataset loading)**

---


