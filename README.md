# SWYNEX-Data-Cleaning-Task-1
Data Cleaning &amp; Preparation project completed as part of my Data Analyst Internship at SWYNEX Technologies. The project focuses on cleaning, transforming, validating, and preparing a retail transaction dataset for further analysis using Microsoft Excel.
# 📊 SWYNEX Technologies – Data Cleaning & Preparation

## 📌 Project Overview

This project was completed as part of my **Data Analyst Internship at SWYNEX Technologies**.

The main objective of this task was to take a raw retail transaction dataset and clean, validate, and prepare it for further data analysis.

Data cleaning is an important step in the data analytics process because the quality of the dataset directly affects the accuracy and reliability of the analysis.

---

## 🎯 Objectives

The key objectives of this project were:

- Identify and handle missing values
- Detect and review duplicate records
- Identify inconsistent or incorrect data
- Standardize data formats
- Validate existing data
- Check calculated fields
- Improve overall data quality
- Prepare the dataset for Exploratory Data Analysis (EDA)

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- Data Cleaning
- Data Validation
- Data Transformation
- Excel Formulas
- Sorting & Filtering
- Data Quality Checks

---

## 📂 Dataset

The dataset contains retail transaction information such as:

- Transaction ID
- Customer ID
- Category
- Item
- Price Per Unit
- Quantity
- Total Spent
- Payment Method
- Location
- Transaction Date
- Discount Applied

---

## 🧹 Data Cleaning Process

During the cleaning process, I worked on:

### 1. Missing Values
Identified records containing missing or unavailable information and reviewed them for appropriate handling.

### 2. Duplicate Records
Checked the dataset for duplicate transactions and ensured that duplicate records were properly reviewed.

### 3. Data Consistency
Reviewed inconsistent entries and standardized values where required.

### 4. Data Validation
Used Excel tools and validation techniques to verify the quality and consistency of the dataset.

### 5. Calculated Fields
Reviewed calculated columns such as total spending to ensure that the values were logically consistent with the available data.

### 6. Final Dataset
After cleaning and validation, the dataset was prepared for the next stage of the analytics workflow.

## Sales Analysis & Dashboard

After cleaning the dataset, I performed exploratory data analysis (EDA) using KPIs, descriptive statistics, pivot tables, and charts to understand sales performance.

 ## Key Insights

1. Overall Sales Performance:
   The business generated 1,552,071 in total sales from 12,575 transactions, with 66,276 units sold. The average transaction value was 129.65, while the median was 108.50, indicating that some higher-value transactions are increasing the overall average.

2. Sales Category:
   Butchers recorded the highest sales at 208,118, while Milk Products recorded the lowest sales at 180,112. This shows a noticeable difference in sales contribution across product categories.

3. Payment Method:
   Cash was the highest-performing payment method, accounting for 537,710 in sales, while Digital Wallet recorded the lowest at 507,279. This indicates that cash remained an important payment method in the dataset.

4. Location:
   The Online location/channel generated the highest sales at 791,402, compared with 760,670 for the lowest-performing location/channel. The relatively close values suggest that sales were distributed fairly closely across the locations/channels represented in the data.

5. Monthly Performance:
   January was the highest-performing month, generating 174,421 in sales, while the lowest-performing month generated 129,688. This indicates variation in monthly sales performance and suggests that sales activity changes throughout the year.

6. Yearly Performance:
   2022 recorded the highest sales at 510,329, while 2025 recorded the lowest at 25,548. The large difference should be interpreted in the context of the number of months/transactions available for each year in the dataset, particularly if 2025 represents only a partial year.

7. Discount Status:
   Transactions with discounts ("True") accounted for 4,219 transactions, compared with 4,157 transactions without discounts ("False"). Therefore, discounted transactions were slightly more frequent in the dataset.

8. Transaction Variation:
   Transaction values ranged from 5 to 410, with a standard deviation of 94.75. This indicates substantial variation in individual transaction values, with customers making both relatively small and considerably larger purchases.

9. Overall Finding:
   The analysis shows that sales performance varies across product categories, payment methods, locations/channels, months, years, and discount status. These dimensions provide useful areas for understanding where sales are concentrated and where differences in performance occur.
The analysis workbook contains the KPIs, EDA, pivot tables, charts, and key insights, while the repository also includes screenshots of the dashboard and analysis.


# 🛒 Retail Sales Dashboard | Power BI

An interactive **Retail Sales Dashboard** built using **Microsoft Power BI** to analyze sales performance, customer purchasing patterns, product categories, payment methods, locations, and yearly sales trends.

The dashboard provides an interactive view of retail business performance from **2022 to 2025**.

---

## 📊 Dashboard Preview

![Retail Sales Dashboard](dashboard.png)

> Replace `dashboard.png` with the name of your dashboard screenshot uploaded to this GitHub repository.

---

## 🎯 Project Objective

The main objective of this project is to create an interactive dashboard that helps users:

- Monitor overall sales performance
- Compare sales across different years
- Analyze sales by product category
- Understand monthly sales trends
- Compare sales by location
- Analyze payment methods
- Analyze discounted vs non-discounted transactions
- Compare **2025 sales with 2022 sales**
- Interactively filter the dashboard using slicers

---

## 📌 Key KPIs

The dashboard includes the following key performance indicators:

| KPI | Description |
|---|---|
| 💰 Total Sales | Overall sales generated |
| 📦 Total Quantity | Total quantity of products sold |
| 💵 Average Unit Price | Average price per unit |
| 🛍️ Average Order Value | Average value of an order |
| 📈 2025 vs 2022 | Percentage change in sales between 2025 and 2022 |

---

## 📈 Dashboard Visuals

The dashboard contains multiple interactive visualizations:

### 1. Sales by Category
A bar chart showing total sales across different product categories.

### 2. Sales by Month & Year
A line/area chart used to compare monthly sales trends across different years.

### 3. Sales by Payment Method
A donut chart showing the distribution of total spending across payment methods.

### 4. Sales by Location
A column chart comparing sales between different locations.

### 5. Sales by Year
A column chart comparing total sales from **2022 to 2025**.

### 6. Sales by Category Treemap
A treemap providing a visual comparison of sales contribution across product categories.

### 7. Discount Analysis
A donut chart showing the distribution of transactions based on whether a discount was applied.

---

## 🎛️ Interactive Features

The dashboard includes interactive slicers for:

- **Payment Method**
- **Location**
- **Category**
- **Year**

Users can select different combinations of filters and analyze the corresponding changes throughout the dashboard.

### 🔄 Reset Button

A **Reset** button has also been added to clear the slicer selections and return the dashboard to its default view.

---

## 🧮 DAX Measures

DAX was used to create calculated measures for KPI analysis and year-to-year comparison.

Example:

```DAX
Sales Change % 2025 vs 2022 =
DIVIDE(
    [Sales 2025] - [Sales 2022],
    [Sales 2022],
    0
)

## 📈 Outcome

The final cleaned dataset provides a more structured and consistent foundation for:

- Exploratory Data Analysis
- Data Visualization
- Dashboard Development
- Business Insights

This project helped me gain practical experience in preparing real-world data for analytics.

---

## 🚀 Future Work

The cleaned dataset can be further used to perform:

- Exploratory Data Analysis using Excel/SQL
- Business performance analysis
- Customer and sales analysis
- Interactive dashboards using Power BI
- Data-driven insights and reporting

---

## 👨‍💻 Skills Demonstrated

**Excel | Data Cleaning | Data Analysis | Data Validation | Data Preparation | Data Visualization Preparation**
