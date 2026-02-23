# 📊 E-Commerce Sales Analytics & Customer Insights

A complete end-to-end Data Analytics project analyzing e-commerce sales data (2022–2024) to generate actionable business insights for revenue growth, customer retention, and inventory optimization.

---

## 🚀 Project Overview

ShopSmart is a growing e-commerce company selling:

* Electronics
* Clothing
* Home & Kitchen

Despite collecting large volumes of transactional data, the company lacked structured insights to support data-driven decisions.

This project transforms raw transactional data into meaningful insights through:

* Data cleaning
* Feature engineering
* Exploratory data analysis
* Customer segmentation
* Revenue & product analysis
* Business recommendations

---

## 🎯 Business Objectives

* Analyze historical sales performance (2022–2024)
* Identify revenue trends and seasonality
* Segment customers based on lifetime value
* Evaluate product performance
* Assess discount effectiveness
* Analyze payment behavior
* Optimize inventory planning
* Provide data-driven business recommendations

---

## 📁 Datasets Used

### 1️⃣ Sales Dataset (`sales_dataset.csv`)

Contains transaction-level data:

* order_id
* customer_id
* product_id
* category
* product_name
* quantity
* price
* discount_percent
* order_date
* payment_method
* city

---

### 2️⃣ Customer Dataset (`customer_data.csv`)

Contains customer demographics:

* customer_id
* customer_name
* age
* gender
* signup_date
* email

---

### 3️⃣ Product Inventory Dataset (`product_inventory.csv`)

Contains stock details:

* product_id
* product_name
* category
* stock_quantity
* reorder_level

---

### 4️⃣ Marketing Campaign Dataset (`marketing_campaigns.csv`)

Contains campaign details:

* campaign_id
* campaign_name
* start_date
* end_date
* budget
* channel

---

## 🧹 Data Cleaning & Preprocessing

Key steps performed:

* Removed duplicate records
* Handled missing values (emails, discounts, stock levels)
* Standardized city names and gender values
* Removed invalid transactions (negative quantity)
* Converted date columns to datetime format
* Ensured consistent data types

---

## 🛠 Feature Engineering

New features created:

* `total_price = quantity × price`
* `discounted_price`
* Year / Month / Quarter
* Day of week
* Weekend flag
* Holiday season flag
* Customer lifetime metrics:

  * Total orders
  * Total revenue
  * Average order value
  * Days since last purchase
* Customer segmentation (Low / Medium / High Value)
* Inventory reorder flag

---

## 📈 Exploratory Data Analysis

### Revenue Analysis

* Revenue by category
* Monthly revenue trends
* Seasonal performance (Oct–Dec peak)

### Customer Analysis

* Revenue by age group
* Gender distribution
* City-wise revenue
* High-value customer contribution

### Product Analysis

* Top 10 products by revenue
* Quantity sold by category
* Revenue concentration

### Discount & Payment Analysis

* Discount vs Quantity relationship
* Payment method distribution
* Weekend vs Weekday sales

### Inventory Analysis

* Products below reorder level
* Category-wise stock imbalance

---

## 📊 Key Insights

* A small percentage of customers contribute a major share of total revenue.
* Moderate discounts increase sales volume more effectively than heavy discounts.
* Metro cities generate the majority of sales.
* Some fast-moving products frequently fall below reorder level.

---

## 💡 Business Recommendations

* Focus marketing on high-value customers.
* Optimize discount strategy instead of offering flat high discounts.
* Increase inventory for fast-moving electronics.
* Strengthen marketing efforts in top-performing cities.
* Implement loyalty programs to improve retention.
* Use demand forecasting to reduce stock-outs.

---

## 🧪 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📊 Sample Visualizations

The project includes:

* Revenue by Category (Bar Chart)
* Monthly Revenue Trend (Line Plot)
* Customer Segmentation (Bar / Pie Chart)
* Discount vs Quantity (Scatter Plot)
* Top 10 Products (Horizontal Bar)
* Inventory Reorder Analysis
* Correlation Heatmap

---

## 🔁 Reproducibility

Random seed was set to ensure consistent dataset generation and reproducible results across multiple runs.

---

## 📂 Project Structure

```
├── sales_dataset.csv
├── customer_data.csv
├── product_inventory.csv
├── marketing_campaigns.csv
├── EDA_notebook.ipynb
└── README.md
```

---

## 📌 Future Improvements

* Sales forecasting using machine learning
* Customer churn prediction
* Real-time dashboard using Power BI / Streamlit
* Recommendation system
* Campaign ROI analysis

---

## 👩‍💻 Author

Your Name
Final Year – AI/ML Engineering
Open to Data Analyst / Business Analyst roles

---

# 🌟 Why This Project Stands Out

* End-to-end analytics pipeline
* Realistic synthetic dataset
* Business-focused insights
* Clean feature engineering
* Customer lifetime value modeling
* Clear business recommendations
* Reproducible workflow

---

