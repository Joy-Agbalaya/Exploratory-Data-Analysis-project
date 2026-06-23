# Exploratory Data Analysis (EDA) Project: E-Commerce Dataset

## Project Overview
This project involves performing an Exploratory Data Analysis on a cleaned e-commerce dataset using Microsoft Excel. The goal was to uncover hidden patterns, trends, and outliers within the data by calculating descriptive statistics, detecting anomalies, and visualizing sales trends across a three year period.

## Tool Used
Microsoft Excel

## Dataset Description
The dataset is the same e-commerce dataset cleaned in Week 1, containing 1,200 rows and 14 columns. It covers e-commerce transaction records including quantity, unit price, items in cart, and total price across the period of 2023 to 2025.

## EDA Steps Performed

**1. Descriptive Statistics Summary**
Calculated key statistics across the Quantity, Unit Price, Items in Cart, and Total Price columns including:
- Count: 1,200 records across all key columns
- Mean Unit Price: $356.41 and Mean Total Price: $1,053.97
- Median Unit Price: $364.21 and Median Total Price: $823.62
- Mean and Median Quantity and Items in Cart both returned a value of 3 and 5 respectively

**2. Outlier Detection Using Interquartile Range (IQR)**
Applied the IQR method to detect outliers in the Total Price column:
- Q1 (25th percentile): $410.52
- Q3 (75th percentile): $1,578.48
- Interquartile Range: $1,167.96
- Lower Bound: -$1,341.41
- Upper Bound: $3,330.41

The outlier distribution summary revealed that 1,192 records (99.33%) fell within the normal range while only 8 records (0.67%) were identified as outliers, indicating a very clean and consistent dataset.

**3. Monthly Sales Trend Analysis**
Used a Pivot Table to summarize the total sales by month and visualized the results using a bar chart showing the Monthly Sales Trend from 2023 to 2025. Key observations include:
- June 2024 recorded the highest total sales at $68,068.54
- May 2023 followed closely with $63,836.84
- The overall grand total of sales across the dataset was $1,264,761.96
- Sales showed a gradual decline from the peak months, suggesting seasonal patterns in customer purchasing behavior

## File Structure
The project is contained in a single Excel file with multiple sheets organized as follows:
- Descriptive_Statistics: Summary of count, mean and median across key columns
- Outlier_Detection: IQR based outlier analysis and distribution summary
- Sales_Trend: Pivot table and bar chart showing monthly sales from 2023 to 2025

## Key Takeaways
This project deepened my understanding of how to interrogate a dataset beyond surface level numbers. Identifying that only 0.67% of the data contained outliers confirmed the effectiveness of the data cleaning done in Week 1. The sales trend analysis also revealed meaningful patterns in customer purchasing behavior that could support business decision making.
