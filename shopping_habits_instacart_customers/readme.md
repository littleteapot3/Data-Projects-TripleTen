
# 🛒 Shopping Habits of Instacart Customers

Welcome to the Instacart Exploratory Data Analysis (EDA) project!  
This project explores customer behavior on the Instacart grocery delivery platform by analyzing shopping patterns using real-world anonymized data.

---

## 📌 Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Installation & Setup](#installation--setup)
- [How to Use](#how-to-use)
- [Features](#features)
- [Insights & Visualizations](#insights--visualizations)
- [Credits](#credits)

---

## 📖 Project Description

This project was developed as part of a data analysis sprint. It focuses on cleaning, analyzing, and visualizing Instacart grocery shopping data to uncover patterns in customer behavior. The analysis aims to answer questions like:

- What time of day and which days of the week do people shop?
- How long do customers typically wait between orders?
- What are the most popular and most frequently reordered products?
- Which items do customers tend to add to their carts first?

This analysis enables us to gain a deeper understanding of user preferences and shopping habits—valuable insights for product recommendations, inventory planning, and targeted marketing.

---

## 🗃️ Dataset

The project uses a modified version of the 2017 Instacart Kaggle dataset, which includes:

- `instacart_orders.csv`: Order-level data per customer  
- `products.csv`: Product metadata  
- `order_products.csv`: Line items mapping products to orders  
- `aisles.csv`: Aisle category metadata  
- `departments.csv`: Department metadata  

**Note**: This dataset was intentionally modified to include missing and duplicate values for the purpose of practicing data cleaning techniques.

---

## ▶️ How to Use

1. Open the main notebook file.
2. Run the cells from top to bottom.
3. Each section includes Markdown explanations and comments to guide your understanding.
4. Visualizations are generated using `matplotlib` and `seaborn`.

The notebook follows a clear flow: data loading → cleaning → exploration → insight generation.

---

## ✨ Features

- Cleaned and prepared five interlinked datasets
- Identified and handled missing and duplicate values
- Generated visual insights on:
  - Shopping times by hour and weekday
  - Time delay between customer orders
  - Product popularity and reorder frequency
  - First items added to cart
- Clear and modular code with explanatory markdown throughout

---

## 📊 Insights & Visualizations

### 🛍️ Shopping Patterns
- **Time of Day**: Orders peak between 7 AM and 8 PM, with a sharp decline afterward.
- **Day of Week**: Sunday and Monday see the highest order volume—likely restocking days.
- **Order Frequency**: Many customers reorder weekly or monthly, often on weekends.

### 🥦 Product Preferences
- **Popular Products**: Organic produce (e.g., Bananas, Organic Strawberries, Spinach) dominate the top 20.
- **Reorder Behavior**: Customers show strong loyalty to specific items, especially organic ones.
- **First Carted Items**: Bananas are the most frequent first item; sodas are a standout non-organic entry.

### 📈 Visual Highlights
- **Hourly Order Distribution**: Bar chart of orders by hour shows daytime peak.
- **Orders by Weekday**: Line chart emphasizes weekend and early-week spikes.
- **Days Since Prior Order**: Histogram shows weekly (7-day) and monthly (30-day) clustering.
- **Top Products**: Bar charts display the frequency of popular and reordered items.
- **Cart Behavior**: Stacked bar chart reveals which items are first added to carts.

---

## 🤝 Credits

This project was created as part of the **TripleTen Data Science Program**.  
Special thanks to:

- **Instacart** for the original dataset  
