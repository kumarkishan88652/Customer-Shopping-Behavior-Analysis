# 🛒 Customer Shopping Behavior Analysis

<p align="center">
  <b>End-to-End Data Analytics Project using Python, PostgreSQL, SQL & Power BI</b>
</p>

<p align="center">
Data Cleaning • Business Analysis • Customer Segmentation • Dashboarding
</p>

---

# 📖 Project Overview

This project focuses on analyzing customer shopping behavior using transactional purchase data from **3,900 customers** across multiple product categories.

The objective is to identify customer patterns, spending habits, subscription trends, product performance, and generate actionable business insights using data analytics techniques.

The project follows a complete analytics workflow:

**Data Collection → Data Cleaning → SQL Analysis → Visualization → Business Recommendations**

---

# 🎯 Business Objectives

* Understand customer purchasing behavior
* Identify revenue-driving customer segments
* Analyze subscription impact on revenue
* Study discount effectiveness
* Discover high-performing products
* Build an interactive dashboard for decision-making

---

# 📊 Dataset Information

| Metric         | Value                       |
| -------------- | --------------------------- |
| Total Rows     | 3,900                       |
| Total Columns  | 18                          |
| Missing Values | 37 (Review Rating Column)   |
| Data Type      | Transactional Customer Data |

### Features Included:

### Customer Information

* Age
* Gender
* Location
* Subscription Status

### Purchase Information

* Product Category
* Item Purchased
* Purchase Amount
* Discount Applied
* Purchase Frequency

### Additional Attributes

* Shipping Type
* Color
* Season
* Size
* Review Rating

---

# 🛠️ Tech Stack

| Tool             | Purpose                  |
| ---------------- | ------------------------ |
| Python           | Data Cleaning & Analysis |
| Pandas           | Data Manipulation        |
| PostgreSQL       | Database Storage         |
| SQL              | Business Queries         |
| Power BI         | Dashboard Creation       |
| Jupyter Notebook | Development Environment  |

---

# 🧹 Data Cleaning & Preprocessing

Performed multiple preprocessing tasks:

✅ Missing value handling

✅ Column standardization

✅ Feature engineering

✅ Data consistency checks

✅ PostgreSQL integration

### Cleaning Steps:

* Filled missing review ratings using category median
* Converted column names into snake_case format
* Created customer age groups
* Generated purchase frequency features
* Removed redundant columns
* Loaded cleaned data into PostgreSQL

---

# 📈 Exploratory Data Analysis

Analysis performed on:

* Customer demographics
* Revenue distribution
* Subscription trends
* Purchase frequency
* Product preferences
* Discount impact
* Customer behavior

---

# 🗄 SQL Business Analysis

## Revenue Analysis

* Revenue by Gender
* Revenue by Age Group
* Subscriber vs Non-Subscriber Revenue

## Customer Behavior Analysis

* High Spending Discount Users
* Repeat Buyer Analysis
* Customer Segmentation

## Product Analysis

* Top Rated Products
* Most Purchased Products
* Discount Dependency Analysis

## Operations Analysis

* Shipping Type Comparison
* Purchase Frequency Analysis

---

# 👥 Customer Segmentation

Customers were categorized into:

| Segment   | Description          |
| --------- | -------------------- |
| New       | Low purchase history |
| Returning | Moderate activity    |
| Loyal     | Frequent purchases   |

---

# 📉 Power BI Dashboard

Dashboard provides:

* KPI Metrics
* Revenue Insights
* Category Analysis
* Subscription Trends
* Customer Segmentation
* Age Group Analysis

### Subscription Growth

* Introduce premium benefits for subscribers

### Loyalty Programs

* Reward repeat customers

### Discount Optimization

* Improve margin control strategies

### Product Positioning

* Promote high-rated products

### Targeted Marketing

* Focus on high-revenue customer groups

---

# 📂 Project Structure

customer-shopping-behavior-analysis/
├── Customer-Shopping-Behaviour-Analysis.ipynb
├── customer_behaviour_dasboard.pbix
├── customer_shopping_behaviour.csv
├── sql_query_anylises.sql
├── Customer Shopping Behaviour Analysis.pdf
├── README.md
└── LICENSE

# 🔮 Future Improvements

* Machine Learning integration
* Predictive customer analytics
* Real-time dashboards
* Automated reporting system

# 👨‍💻 Author

**Kishan Kumar**

LinkedIn: https://www.linkedin.com/in/kishan-kumar-singh-0806a13a8

GitHub: https://github.com/kumarkishan88652

⭐ If you found this project useful, consider giving it a star.
