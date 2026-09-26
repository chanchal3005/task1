# Customer Behavior Analysis

## 📌 Project Overview

This project analyzes customer transactions and purchasing behavior to identify **customer segments, purchase patterns, and potential churn risks** for Alfido Tech.

The analysis uses **RFM (Recency, Frequency, Monetary) analysis** to segment customers and understand their value and engagement.

## 🎯 Objectives

* Clean and prepare customer transaction data
* Perform feature engineering
* Segment customers using RFM analysis
* Profile different customer segments
* Analyze purchasing patterns and trends
* Identify potential churn-risk customers
* Provide actionable recommendations for customer engagement

## 📂 Dataset

**Source:** Kaggle – Customer Behavior Analysis

[Dataset Link](https://www.kaggle.com/datasets/bhanupratapbiswas/customer-behavior-analysis)

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## 🔍 Analysis Performed

### 1. Data Cleaning

* Checked missing values
* Removed duplicate records
* Converted date columns
* Created additional time-based features

### 2. RFM Customer Segmentation

Customers were analyzed using:

| Metric    | Description                           |
| --------- | ------------------------------------- |
| Recency   | How recently the customer purchased   |
| Frequency | How frequently the customer purchased |
| Monetary  | How much the customer spent           |

Customers were grouped into segments such as:

* **High Value**
* **Loyal**
* **Potential**
* **At Risk**

### 3. Purchase Pattern Analysis

The project analyzes:

* Monthly purchase trends
* Product category performance
* Payment method usage
* Customer spending patterns
* Purchase frequency

### 4. Churn Risk Analysis

Customers with higher recency values and lower engagement were identified as potential **at-risk customers** for targeted retention campaigns.

## 📊 Visualizations

### Customer Segment Distribution

![Customer Segments](charts/customer_segments.png)

### Monthly Purchase Trend

![Monthly Purchases](charts/monthly_purchases.png)

### Category Sales

![Category Sales](charts/category_sales.png)

### Frequency vs Spending

![Frequency vs Spending](charts/frequency_vs_spending.png)

## 💡 Key Recommendations

1. Reward high-value customers with loyalty benefits and exclusive offers.
2. Encourage loyal customers through personalized promotions.
3. Target potential customers with relevant product recommendations.
4. Run reactivation campaigns for at-risk customers.
5. Use purchase history and product preferences for targeted marketing.

## 📁 Project Files

* 📓 [Jupyter Notebook](Customer_Behavior_Analysis.ipynb)
* 📄 [Executive Summary](Executive_Summary.pdf)
* 📈 [Charts](charts/)

## 📋 Deliverables

* Jupyter/Colab notebook containing complete analysis and visualizations
* PDF report containing key findings, customer segments, and recommendations

