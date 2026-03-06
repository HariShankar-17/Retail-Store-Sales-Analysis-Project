# Retail Store Sales Analysis

## Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on a retail store dataset to uncover business insights related to sales performance, product trends, regional performance, and customer purchasing behavior.

The goal of this project is to simulate how a data analyst would analyze retail data and answer key business questions for executives.

Dataset contains **2500 retail transactions** with **11 columns** including order information, product details, pricing, discounts, and revenue.

---

## Business Problem
Retail companies generate large amounts of sales data, but without proper analysis it is difficult to extract meaningful insights.

This project answers important business questions such as:

- How revenue changes over time
- Which products generate the most revenue
- Which regions perform best
- How discounts impact revenue
- Customer purchasing behavior patterns
- Distribution and outliers in order revenue

---

## Dataset Information

**Dataset Size**
- Rows: 2500
- Columns: 11

**Features**

| Column | Description |
|------|-------------|
| Order_ID | Unique order identifier |
| Order_Date | Date of order |
| Region | Sales region |
| City | City where order was placed |
| Category | Product category |
| Product | Product name |
| Quantity | Number of units sold |
| Unit_Price | Price per unit |
| Discount_Percent | Discount applied |
| Revenue | Final revenue generated |
| Payment_Mode | Payment method |

---

## Tools & Technologies Used

Python  
Pandas  
Matplotlib  
Seaborn  
Jupyter Notebook  

---

## Project Workflow

### 1. Data Understanding
- Checked dataset shape
- Inspected data types
- Summary statistics
- Identified categorical variables

### 2. Data Preparation
- Converted `Order_Date` to datetime
- Created `Month_Year` feature for time analysis
- Copied dataset for safe manipulation

---

## Business Questions Answered

### Phase 1 – Business Performance

1. **How is revenue trending over time?**
   - Monthly revenue analysis using time series plots
   - Identification of peak and low-performing months

2. **Which products generate the highest revenue?**
   - Product ranking based on total revenue

---

### Phase 2 – Regional Performance

3. **Which region contributes the most revenue?**
   - Revenue comparison between North, South, East, and West

4. **Best performing city in each region**
   - Grouped analysis using Region + City

---

### Phase 3 – Product & Customer Behavior

5. **Top products by quantity sold**
   - Comparison between quantity vs revenue impact

6. **Impact of discounts on revenue**
   - Scatter plot analysis

**Key Insight**
Small discounts (~5%) increased revenue, but higher discounts reduced profitability.

---

### Phase 4 – Revenue Distribution Analysis

7. **Order revenue distribution**
   - Histogram visualization
   - Identified right-skewed distribution

8. **Revenue outliers across product categories**
   - Boxplot analysis to detect extreme values

---

### Phase 5 – Advanced Data Analysis

9. **Revenue distribution by category**
   - Violin plot for deeper distribution analysis

10. **Correlation analysis**
   - Heatmap to identify relationships between:
  - Quantity
  - Unit Price
  - Discount
  - Revenue

11. **Overall relationship visualization**
   - Pairplot for multivariable exploration

---

## Key Insights

- Electronics products generate the highest revenue.
- Revenue strongly correlates with **Unit Price**.
- A **5% discount increased revenue**, but higher discounts reduced profitability.
- Revenue distribution is **right-skewed**, meaning most orders are small but a few large transactions exist.
- Some product categories show **high revenue variability and outliers**.

---

## Visualizations Used

- Line Plot
- Bar Chart
- Scatter Plot
- Histogram
- Box Plot
- Violin Plot
- Correlation Heatmap
- Pair Plot

These visualizations help uncover trends, relationships, and anomalies within the dataset.

---

## Project Structure
