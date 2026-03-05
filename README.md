# Retail Revenue & Customer Analytics

This project analyzes an e-commerce retail dataset to understand revenue trends, customer purchasing behavior, and customer lifetime value.

The analysis covers data cleaning, exploratory analysis, revenue concentration, retention analysis, customer lifetime value, and customer segmentation.

Dataset contains over **500,000 retail transactions**.

---

# Dataset

**Source**

UCI Online Retail II Dataset

The dataset includes transactional data from a UK-based online retailer between **2009 and 2010**.

Main fields include:

- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

---

# Project Structure
retail-kpi-analysis
│
data
clean_retail.csv
online_retail.xlsx
│
notebooks
data_cleaning.ipynb
eda_overview.ipynb
kpi_analysis.ipynb
cohort_analysis.ipynb
clv_analysis.ipynb
rfm_segmentation.ipynb
│
dashboard
powerbi_dashboard.pbix
│
README.md
requirements.txt

---

# Tools Used

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Power BI

---

# Analysis Overview

The project follows a full analytics workflow:

1. Data Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Revenue KPI Analysis  
4. Product Revenue Distribution  
5. Customer Retention (Cohort Analysis)  
6. Customer Behavior Analysis  
7. Customer Lifetime Value (CLV)  
8. Customer Segmentation (RFM)  
9. Power BI Dashboard

---

# Data Cleaning

Data preparation steps include:

- Removed cancelled invoices
- Removed missing customer IDs
- Filtered negative quantities and prices
- Created revenue column (`Revenue = Quantity × Price`)
- Generated month and order level datasets

---

# Exploratory Data Analysis

Exploratory analysis was conducted to understand overall business patterns.

Key visualizations include:

- Revenue by country
- Monthly order trends
- Customer purchase distribution

Insights:

- Revenue is highly concentrated in the UK market
- Orders increase significantly during holiday seasons
- Customer purchase behavior shows a heavy-tailed distribution

---

# Revenue KPI Analysis

Key business metrics analyzed:

- Monthly revenue trends
- Average order value (AOV)
- Customer count
- Product revenue ranking

Insights:

Revenue increased significantly in late 2010, likely driven by seasonal shopping demand.

---

# Product Revenue Concentration (Pareto Analysis)

Product revenue distribution was analyzed to identify revenue concentration.

Findings:

Approximately **23% of products generate 80% of total revenue**, indicating a strong **Pareto distribution** typical in retail datasets.

This suggests that focusing on top-performing products can significantly impact revenue performance.

---

# Customer Retention (Cohort Analysis)

Customer retention was analyzed using cohort analysis.

Customers were grouped by their **first purchase month** and tracked across future months.

Findings:

- Retention drops sharply after the first purchase
- Repeat purchase rates stabilize around **30–40%**
- Seasonal activity increases during holiday periods

This indicates that most customers are one-time buyers while a smaller segment forms a stable repeat customer base.

---

# Customer Lifetime Value (CLV)

Customer lifetime value was estimated using historical revenue per customer.

Findings:

Customer value distribution is highly skewed.

The **top 10% of customers generate approximately 60% of total revenue**, highlighting the importance of high-value customers.

This suggests that targeted retention and loyalty programs for high-value customers could significantly increase revenue.

---

# Customer Segmentation (RFM)

Customers were segmented using **RFM analysis** based on:

- Recency (how recently a customer purchased)
- Frequency (number of purchases)
- Monetary (total revenue)

Customers were grouped into:

- VIP customers
- Loyal customers
- Potential customers
- At-risk customers

This segmentation helps identify:

- High value customers to retain
- Potential customers to nurture
- At-risk customers who may churn

---

# Power BI Dashboard

A Power BI dashboard was created to visualize key business metrics.

Dashboard includes:

- Revenue trends
- Product performance
- Customer distribution
- Key KPIs

The dashboard provides an interactive view of the retail business performance.

---

# Key Business Insights

Major findings from the analysis include:

- Revenue shows strong seasonal trends
- Product revenue follows a Pareto distribution
- Most customers purchase only once
- A small group of high-value customers generates the majority of revenue
- Customer retention stabilizes after initial churn

These insights highlight the importance of **customer retention strategies and high-value customer targeting**.

---

# Future Improvements

Potential extensions to the project include:

- Customer churn prediction
- Customer lifetime value modeling with probabilistic models
- Marketing campaign impact analysis
- Recommendation systems

---

# Author

Chuhao Nie

MS in Business Analytics  
Washington University in St. Louis