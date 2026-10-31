PROJECT REPORT
TITLE: NIKE SALES DATA CLEANING, PREPROCESSING AND ANALYSIS
NAME: MOHAMMED JASIL K
                      		          BATCH: DA55
           INDEX (Table of Contents)

1.	Title Page
2.	Index
3.	Executive Summary / Abstract
4.	Introduction & Business Problem
5.	Project Objectives
6.	Dataset Description
7.	Tools and Technologies Used
8.	Data Cleaning and Preprocessing
9.	Exploratory Data Analysis (EDA) & Insights
10.	Conclusion & Recommendations

 1. Executive Summary / Abstract
This project focuses on cleaning, preprocessing, and analyzing the Nike Sales dataset using Python and Data Analytics methodologies. The primary goal was to transform raw, unorganized sales data into a structured format, enabling accurate business performance tracking, revenue analysis, and regional sales distribution evaluation.

2. Introduction & Business Problem
Nike operates globally across multiple product lines and regions. Raw sales datasets often contain inconsistencies, missing values, incorrect data formats, and duplicate records. Without proper data cleaning, business metrics can become skewed, leading to inaccurate financial and inventory decisions.

3. Project Objectives
●	Clean missing, inconsistent, and duplicate data in the Nike sales dataset.
●	Standardize date formats, numeric data types, and text values for smooth analysis.
●	Perform Exploratory Data Analysis (EDA) to uncover sales trends and top-performing categories.
●	Visualize key business metrics using Python charts and Power BI dashboards.
 
4. Dataset Description
●	Dataset Name: Nike Sales Dataset
●	Key Columns: Order ID, Order Date, Region, State, City, Product Category, Price per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin, Sales Method.
●	Format: CSV / Excel
5. Tools and Technologies Used
●	Programming Language: Python
●	Libraries: Pandas, NumPy, Matplotlib, Seaborn
●	Environment: Google Colab / Jupyter Notebook
●	Visualization: Power BI Desktop / Excel
●	Version Control: GitHub
6. Data Cleaning and Preprocessing
6.1 Handling Missing Values
●	Identified null/missing values in numerical fields like Total Sales and Units Sold.
●	Imputed missing values using median/mean calculations where necessary or removed incomplete records to maintain data integrity.
 
6.2 Data Type Conversions
●	Converted string formatted dates into proper datetime64[ns] format.
●	Ensured currency values and unit counts were properly cast to float and int types.
6.3 Removing Duplicates & Text Normalization
●	Removed duplicate row entries based on Order ID.
●	Trimmed leading/trailing whitespaces and unified letter casing in product categories and regional names.
6.4 Outlier Detection
●	Applied IQR (Interquartile Range) methods to inspect extreme spikes in sales metrics.
7. Exploratory Data Analysis (EDA)
●	Category Sales Distribution: Evaluated which footwear and apparel items generate the highest total revenue.
●	Regional & Channel Analysis: Analyzed sales across different regions (West, East, Midwest, South) and sales methods (In-store, Online, Outlet).
●	Monthly Sales Trends: Tracked time-series revenue patterns to identify seasonal demand peaks.
 

8. Conclusion & Recommendations
●	Data Quality: Successfully transformed raw Nike sales data into a reliable, cleaned dataset ready for business intelligence reporting.
●	Key Takeaway: Online and Outlet channels demonstrated higher margin trends, while specific footwear categories led overall revenue.
●	Next Steps: Integrate the cleaned dataset into Power BI for interactive dashboard monitoring.

