# Retail Sales Intelligence Analysis

## Project Overview
This project performs an end-to-end analysis of a retail sales dataset to uncover business insights related to revenue performance, customer segments, product demand, and operational efficiency.

The analysis combines **Python-based exploratory data analysis (EDA)** with a **Power BI dashboard** to translate raw transactional data into clear business insights that could support managerial decision-making.

The goal of this project was to simulate the type of analysis a **Data Analyst or Business Analyst** would perform to help a retail company understand:

- Where revenue is coming from
- Which products and categories drive sales
- Which regions perform best
- Customer segment contributions
- Operational efficiency in product delivery

---

# Dataset Description

The dataset contains transactional retail sales data with the following key attributes:

- Order ID
- Order Date
- Ship Date
- Customer ID
- Customer Segment
- Product Category
- Sub-Category
- Region
- Sales value

### Dataset Characteristics

| Metric | Value |
|------|------|
| Total Records | 9,800 |
| Time Period | 2015 – 2018 |
| Variables | 18 |
| Total Revenue | ~2.26 Million |

---

# Project Workflow

The analysis was performed in two main stages.

## 1. Data Analysis (Python)

The first stage focused on **data exploration and insight generation using Python**.

### Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Key Steps

#### Data Cleaning
- Converted date columns into proper datetime format
- Created new variables such as **Delivery Days**
- Checked for missing values and data consistency

#### Exploratory Data Analysis
The dataset was analyzed to understand:

- Overall revenue performance
- Sales trends over time
- Product category performance
- Regional performance
- Customer segmentation
- Operational delivery performance

---

# Key Business Insights

## 1. Revenue Performance

Total revenue generated across the dataset was approximately:

**$2.26 Million**

Revenue showed **strong growth momentum toward the later period**, suggesting either:

- Increased demand
- Successful marketing or promotions
- Expansion of the product portfolio

The upward trend indicates that the company experienced **improving sales performance over time**.

---

## 2. Product Category Performance

Sales analysis revealed that **Technology products were the top revenue drivers**, followed by Furniture and Office Supplies.

### Implication for Business

Technology products likely have:

- Higher customer demand
- Higher average selling prices
- Stronger profit potential

The company could consider:

- Expanding the technology product line
- Increasing marketing efforts for high-performing products
- Ensuring adequate inventory availability

---

## 3. Sub-Category Performance

Further analysis showed that specific products contributed significantly to overall revenue.

Top performing sub-categories included:

- Phones
- Chairs
- Storage
- Tables

### Business Implication

These products represent **core revenue drivers**.

Management could focus on:

- Increasing supply chain reliability for these items
- Cross-selling related products
- Offering bundled promotions

---

## 4. Regional Sales Performance

Sales were analyzed across four regions:

- West
- East
- Central
- South

### Observations

The **West region generated the highest sales**, while the **South region generated the lowest revenue**.

### Business Interpretation

This could indicate:

- Higher demand in western markets
- Better distribution networks in those regions
- Potential underperformance in southern markets

The company could investigate:

- Market penetration strategies for weaker regions
- Marketing campaigns targeted at underperforming markets

---

## 5. Customer Segment Analysis

Revenue contributions by customer segment:

- Consumer segment generated the majority of revenue
- Corporate segment contributed moderate revenue
- Home Office segment contributed the least

### Business Implication

The company’s primary market appears to be **consumer customers rather than business clients**.

Strategic options include:

- Expanding B2B sales
- Creating corporate partnerships
- Offering business-focused product packages

---

## 6. Delivery Performance

A delivery performance metric was created:

**Delivery Days = Ship Date − Order Date**

### Key Findings

Average delivery time was approximately:

**4 days**

Delivery times were **relatively consistent across regions**, suggesting that logistics operations are functioning efficiently.

### Operational Insight

Since delivery times do not vary significantly by region, the lower revenue in certain regions is likely due to **demand factors rather than logistical issues**.

---

# Power BI Dashboard

To present insights visually, a **two-page interactive Power BI dashboard** was developed.

## Page 1 — Executive Overview

This page provides a high-level summary for decision makers:

- Total Revenue KPI
- Average Order Value KPI
- Monthly Revenue Trend
- Sales by Category
- Sales by Region

This allows executives to quickly assess **overall business performance**.

### Dashboard Preview

![Executive Dashboard](dashboard_page1.png)

---

## Page 2 — Detailed Insights

The second page provides deeper operational insights:

- Sales by Customer Segment
- Top 10 Sub-Categories
- Average Delivery Time by Region
- Distribution of Delivery Days

These visuals help identify **drivers of revenue and operational efficiency**.

### Dashboard Preview

![Detailed Insights](dashboard_page2.png)

---

# Key Skills Demonstrated

This project demonstrates several core data analyst skills:

### Data Analysis
- Data cleaning
- Feature engineering
- Exploratory Data Analysis (EDA)

### Business Analytics
- KPI development
- Revenue trend analysis
- Market segmentation
- Operational performance analysis

### Visualization
- Python visualizations
- Interactive dashboards in Power BI

### Communication
- Translating data findings into **business insights**

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI

---

# Conclusion

This project demonstrates how raw transactional data can be transformed into meaningful business insights using data analysis and visualization tools.

By combining Python analysis with Power BI dashboards, the project provides both **technical analysis and executive-level reporting**, similar to what would be expected in a real-world business analytics role.

The results highlight key revenue drivers, regional performance differences, and operational delivery insights that could help guide strategic decision-making for a retail company.

