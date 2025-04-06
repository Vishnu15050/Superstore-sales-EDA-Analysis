# Superstore-sales-EDA-Analysis

🛍️ Superstore Sales Analysis – Exploratory Data Analysis (EDA)
📌 Project Summary:
This project is an end-to-end Exploratory Data Analysis (EDA) on the Sample Superstore dataset using Python. The objective is to uncover patterns, trends, and actionable business insights from retail sales data.

We examined key performance indicators like Sales, Profit, Discount, Quantity, across multiple dimensions such as State, Region, Category, Sub-Category, and Time.

🎯 Business Objective:
The goal of this analysis is to support business stakeholders by:

Identifying loss-making areas

Understanding profit trends by region and category

Studying the impact of discounts on profitability

Recommending strategies for improving sales and reducing losses

📦 Dataset Overview:
📁 File: Sample - Superstore.csv

🧾 Total Records: 9994 rows × 21 columns

🌎 Country: United States

🕒 Date Range: 2014 – 2017

Main Features:

Customer Orders

Product Categories & Sub-categories

Order Date, Ship Date, Region, State, City

Financials: Sales, Profit, Discount, Quantity

🔍 Step-by-Step Analysis Breakdown:
✅ 1. Data Loading & Initial Exploration
Imported data using pandas

Checked dataset shape, column names, and types using .info()

Used .describe() for basic statistical summary

✅ 2. Data Cleaning
Verified missing values and duplicate rows (none found)

Handled column types and reformatted date columns

✅ 3. Univariate Analysis
Count plots for Ship Mode, Segment, Category

Bar plots for top-selling States, Sub-Categories

Visualized Sales and Profit distributions

✅ 4. Bivariate Analysis
Analyzed Profit vs Discount with scatter plots

Used correlation heatmap for numerical features

Compared Sales & Profit by Region and Category

✅ 5. Time Series Analysis
Converted Order Date to datetime

Analyzed monthly trends in Sales and Profit

Plotted line graphs to visualize time patterns

✅ 6. Outlier Detection
Used Z-score method to detect outliers

Visualized with box plots and highlighted impact on Profit

✅ 7. Statistical Summary
Detailed .describe() output interpreted for Profit, Sales, and Discount

Discussed mean, median, skewness, and variance where necessary

✅ 8. Business Insights & Recommendations
High discount leads to lower profits in many categories

Technology category has high profit margin

Furniture often causes losses with high discount rates

Western region is profitable, while some southern states incur loss

🧠 Key Insights:
Insight	Explanation
🏆 Top-Selling State	California has the highest sales
📉 Loss-Making State	Texas and Illinois show negative profit
💸 Discount Problem	Profit decreases sharply when discounts go beyond 20%
🔁 Repeat Orders	Standard Class shipping is most preferred
⏳ Time Trend	November and December show highest sales due to festive season
🛠️ Technologies & Tools Used:
Python: Pandas, NumPy, Matplotlib, Seaborn

Environment: Google Colab

Visualization: Bar charts, line plots, scatter plots, box plots, heatmaps
