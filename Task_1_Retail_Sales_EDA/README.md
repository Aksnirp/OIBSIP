# 🛍️ Retail Sales Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on a retail sales dataset to uncover business insights, customer purchasing patterns, product performance, and sales trends. The analysis includes data cleaning, descriptive statistics, time-series analysis, customer segmentation, correlation analysis, and actionable business recommendations.

The project was completed as part of the **Oasis Infobyte Internship (OIBSIP)**.

---

## 🎯 Objectives

- Clean and preprocess retail sales data.
- Analyze sales performance over time.
- Understand customer demographics and purchasing behavior.
- Identify high-performing product categories.
- Discover relationships between important business variables.
- Generate actionable business recommendations using data.

---

## 📂 Dataset

**Dataset:** Retail Sales Dataset

The dataset contains transaction-level retail sales information including:

- Transaction ID
- Customer ID
- Date
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

**Source:** Kaggle

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab
- KaggleHub

---

## 📊 Project Workflow

### 1. Data Loading & Cleaning

- Loaded dataset using Pandas.
- Checked dataset dimensions and data types.
- Removed duplicate records.
- Verified missing values.
- Created additional features:
  - Month
  - Month Name
  - Quarter
  - Day of Week
  - Age Group

---

### 2. Descriptive Statistics

Performed statistical analysis including:

- Mean
- Median
- Mode
- Standard Deviation
- Skewness

Visualized distributions using:

- Histograms
- KDE plots

---

### 3. Time Series Analysis

Analyzed sales trends by:

- Monthly Revenue
- Quarterly Revenue
- Day-of-Week Sales Pattern

Visualizations:

- Line Chart
- Bar Charts

---

### 4. Customer & Product Analysis

Analyzed:

- Revenue by Product Category
- Average Order Value
- Gender-wise Purchasing Behavior
- Age Group Spending
- Top 10 Customers

Visualizations:

- Horizontal Bar Charts
- Pie Charts
- Grouped Bar Charts

---

### 5. Advanced Visualizations

Created:

- Monthly Revenue Heatmap
- Correlation Heatmap
- Boxplots for Spending Distribution

These visualizations helped identify:

- Seasonal trends
- Variable relationships
- Spending variability

---

### 6. Executive Summary & Business Recommendations

Generated a business summary including:

- Total Revenue
- Total Transactions
- Average Order Value
- Unique Customers
- Peak Sales Month
- Best Performing Product Category

Recommendations include:

- Increase inventory during peak months.
- Promote high-value product categories.
- Target customers aged 25–45 with personalized campaigns.
- Improve weekday sales through promotions.
- Develop VIP loyalty programs for top customers.
- Enhance performance of low-selling categories.

---

## 📈 Key Insights

- Electronics generated the highest average order value.
- Clear seasonal sales patterns were observed throughout the year.
- Customers aged **25–45** contributed significantly to revenue.
- A small number of customers generated a large proportion of total sales.
- Product category performance varied considerably across months.

---

## 📁 Project Structure

```
Retail-Sales-EDA/
│
├── Retail_Sales_EDA.ipynb
├── retail_sales_dataset.csv
├── images/
│   ├── fig_distributions.png
│   ├── fig_monthly_trend.png
│   ├── Fig_quaterly.png
│   ├── fig_day_of_week.png
│   ├── fig_product_category.png
│   ├── fig_gender_analysis.png
│   ├── fig_age_analysis.png
│   ├── fig_top_customers.png
│   ├── fig_heatmap.png
│   ├── fig_correlation.png
│   └── fig_boxplot.png
├── requirements.txt
└── README.md
```


