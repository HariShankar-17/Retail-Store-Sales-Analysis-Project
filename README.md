cat << 'EOF' > README.md
# 🛒 Retail Store Sales Analysis

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a retail store dataset to uncover meaningful business insights. The goal is to analyze sales performance, product demand, regional revenue distribution, and customer purchasing behavior using Python.

The analysis simulates how a **data analyst would approach real-world business questions** and present insights that help decision-makers improve business strategy.

---

## 📊 Dataset Information

The dataset contains **2500 retail transactions** with **11 features** describing orders, products, pricing, discounts, and revenue.

### Features

| Column | Description |
|------|-------------|
| Order_ID | Unique order identifier |
| Order_Date | Date when the order was placed |
| Region | Sales region |
| City | City where the order occurred |
| Category | Product category |
| Product | Product name |
| Quantity | Number of units sold |
| Unit_Price | Price per unit |
| Discount_Percent | Discount applied on the order |
| Revenue | Final revenue generated |
| Payment_Mode | Payment method used |

---

## 🎯 Project Objectives

The analysis answers key business questions such as:

- How revenue changes over time
- Which products generate the highest revenue
- Which regions contribute the most to company sales
- Which cities perform best within each region
- Which products sell the most by quantity
- How discounts affect revenue
- Distribution of order revenue
- Detection of revenue outliers
- Correlation between business variables

---

## 🛠 Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔎 Project Workflow

### 1️⃣ Data Understanding
- Checked dataset shape
- Inspected data types
- Summary statistics
- Identified categorical and numerical variables

### 2️⃣ Data Preparation
- Converted `Order_Date` to datetime format
- Created `Month_Year` column for time-series analysis
- Created a working copy of the dataset for safe manipulation

### 3️⃣ Exploratory Data Analysis
- Revenue trend analysis
- Product performance analysis
- Regional and city-level analysis
- Discount impact analysis
- Revenue distribution analysis
- Correlation and relationship analysis

---

# 📈 Project Visualizations

Below are the visualizations generated during the analysis.

---

## 1️⃣ City Performance by Region

This chart compares how different cities contribute to revenue within each region.

![City Performance](images/city_performance.png)

---

## 2️⃣ Correlation Heatmap

Shows relationships between numerical variables such as:

- Quantity
- Unit Price
- Discount Percent
- Revenue

Key insight:  
Revenue strongly correlates with **Unit Price**.

![Correlation Heatmap](images/correlation.png)

---

## 3️⃣ Discount vs Revenue

This scatter plot shows how discount percentages affect revenue.

Key insight:

- Small discounts (~5%) can increase revenue
- Larger discounts may reduce profitability

![Discount vs Revenue](images/discount_vs_revenue.png)

---

## 4️⃣ Order Revenue Distribution

This histogram shows how order revenue is distributed.

Observation:

Most orders are **small to medium sized**, while a few large orders create outliers.

![Revenue Distribution](images/order_revenue_distribution.png)

---

## 5️⃣ Overall Relationship Between Variables

Pairplot showing relationships between key numerical variables.

Variables analyzed:

- Quantity
- Unit Price
- Discount Percent
- Revenue

![Overall Relationship](images/overall_relationship.png)

---

## 6️⃣ Revenue Outliers Across Categories

Boxplot visualization showing revenue distribution across categories.

Insight:

The **Electronics category** has wider revenue spread and higher outliers.

![Revenue Outliers](images/revenue_outliers.png)

---

## 7️⃣ Top Selling Products

Bar chart showing the products with the highest quantity sold.

Insight:

High-selling products are not always the highest revenue-generating products.

![Top Selling Products](images/top_selling_product.png)

---

# 💡 Key Insights

- Electronics products generate the highest revenue.
- Revenue strongly correlates with **unit price**.
- A **5% discount produced the highest revenue impact**.
- Higher discounts did not significantly improve revenue.
- Revenue distribution is **right-skewed**, meaning most orders are smaller while a few large transactions dominate.
- Some categories show large **revenue outliers**, indicating premium products or bulk orders.

---

# 📂 Project Structure
