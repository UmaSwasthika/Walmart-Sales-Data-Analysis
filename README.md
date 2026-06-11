Walmart Sales Data Analysis

Project Overview

An end-to-end SQL analysis of Walmart's weekly store sales data (2010–2012), identifying revenue trends, store performance patterns, holiday impact, and top-performing departments.

Tools & Technologies


SQL (SQLite)
DB Browser for SQLite
Dataset: Walmart Recruiting - Store Sales Forecasting (Kaggle)


Dataset

FileDescriptionRowstrain.csvWeekly sales by store and department421,570stores.csvStore type (A/B/C) and size45

Columns in Sales table: Store, Dept, Date, Weekly_Sales, IsHoliday

Columns in Stores table: Store, Type, Size

SQL Concepts Used


SELECT, WHERE, LIMIT
COUNT, COUNT DISTINCT
SUM, AVG, ROUND, MIN, MAX
GROUP BY, ORDER BY
JOIN (combining two tables)
SUBSTR (extracting year from date)


Key Findings

1. Top Performing Stores

Store 20 generated the highest total revenue ($301M), followed by Store 4 ($299M) and Store 14 ($289M). All top stores are Type A (large format).

2. Store Type Performance

Type A stores average $20,099 in weekly sales — more than double the $9,519 average of Type C stores. Store size is a strong predictor of sales volume.

3. Holiday Impact

Holiday weeks average $17,035 in sales vs $15,901 for non-holiday weeks — a 7% uplift. This validates the business case for increased holiday staffing and inventory.

4. Outlier: Store 10

Store 10 (Type B, 126k sqft) ranks 6th overall despite being significantly smaller than the top stores, suggesting unusually high sales efficiency per square foot.

5. Top Departments

Departments 92 ($483M) and 95 ($449M) are the highest revenue generators, consistent with high-frequency consumable categories driving repeat weekly purchases.

6. Year-over-Year Growth

Sales grew approximately 7% from 2010 to 2011 ($2.29B → $2.45B). 2012 data is partial (Jan–Oct only) and not directly comparable.
