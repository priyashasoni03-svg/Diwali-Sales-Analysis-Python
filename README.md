# Diwali-Sales-Analysis-Python
# Diwali Sales Analysis Using Python

## 1. Project Introduction

Diwali is one of India's biggest shopping seasons, offering businesses significant opportunities to increase sales and attract customers. Understanding customer purchasing behaviour during this period can help businesses develop effective marketing strategies, improve customer engagement, and optimise product offerings.

This project focuses on analysing Diwali sales data using Python to understand customer demographics, purchasing patterns, product preferences, and sales performance across different states and occupations.

Using data cleaning, exploratory data analysis (EDA), and data visualisation techniques, the project aims to identify meaningful patterns in customer behaviour and translate them into actionable business insights.

## 2. Business Problem

Retail businesses often collect large amounts of transactional data but may struggle to identify which customer segments contribute most to sales, which products receive the most orders, and which geographical markets perform well.

Without these insights, businesses may find it difficult to target the right customers, allocate marketing budgets effectively, and make informed inventory and promotional decisions.

The objective of this analysis is to explore Diwali sales data and identify customer segments, product categories, and geographical markets that can help retailers make better business decisions.

## 3. Project Objectives

The primary objectives of this project are:

- Clean and prepare the dataset for reliable analysis
- Understand customer demographics, including age groups and gender
- Analyse purchasing behaviour across marital status and occupation
- Identify states contributing the highest number of orders and sales
- Examine product categories and identify frequently ordered products
- Visualise sales patterns using charts and graphs
- Develop business recommendations to improve customer targeting and sales performance

## 4. Dataset Overview

The project uses a Diwali sales dataset containing customer, product, demographic, and transactional information.

**Initial dataset:** 11,251 rows and 15 columns

**Dataset after cleaning:** 11,239 rows and 13 columns

Important columns include:

- `User_ID`: Unique customer identifier
- `Cust_name`: Customer name
- `Product_ID`: Product identifier
- `Gender`: Customer gender
- `Age Group`: Customer age category
- `Age`: Customer age
- `Marital_Status`: Marital status indicator
- `State`: Customer's state
- `Zone`: Geographical zone
- `Occupation`: Customer occupation
- `Product_Category`: Product category
- `Orders`: Number of orders recorded
- `Amount`: Recorded sales amount

## 5. Tools and Technologies

- **Python:** Primary programming language for analysis
- **Pandas:** Data manipulation, cleaning, and aggregation
- **NumPy:** Numerical computing
- **Matplotlib:** Data visualisation
- **Seaborn:** Statistical visualisation and categorical comparisons
- **Jupyter Notebook:** Interactive environment for executing code and documenting findings

## 6. Methodology

### Step 1: Data Loading and Inspection
Imported the CSV dataset using Pandas and examined its dimensions, sample records, column names, and data types.

### Step 2: Data Cleaning
- Removed irrelevant and completely empty columns
- Identified missing values
- Removed rows containing missing values
- Converted the `Amount` column to an integer data type
- Reviewed the remaining columns for analysis

### Step 3: Exploratory Data Analysis
Performed exploratory analysis to investigate customer characteristics, sales distribution, and product performance.

### Step 4: Data Visualisation
Created bar charts and count plots using Matplotlib and Seaborn to compare customer segments, sales amounts, state-level performance, and product order volumes.

### Step 5: Business Interpretation
Used the analysis to identify customer segments and product trends that could inform marketing, inventory planning, and sales strategies.

## 7. Key Areas of Analysis

### Customer Demographics
Examined the distribution of customers by gender and age group to understand the demographic profile of shoppers.

### Gender and Purchasing Behaviour
Compared sales amounts across genders to understand differences in recorded purchasing value.

### Age Group Analysis
Investigated order activity and sales amounts across different age groups to identify potentially valuable customer segments.

### State-Level Sales Performance
Compared the number of orders and total recorded sales across states to identify geographically important markets.

### Occupation and Customer Segmentation
Explored occupation and marital status as customer segmentation variables to support more targeted marketing analysis.

### Product Performance
Examined product categories and ranked individual products by total recorded orders to identify frequently ordered products.

## 8. Key Findings and Conclusion

The analysis explores several dimensions of Diwali shopping behaviour, including customer demographics, purchasing patterns, geographical distribution, and product performance.

The preliminary conclusion from the analysis is that married women in the 26–35 age group, particularly in Uttar Pradesh, Maharashtra, and Karnataka, represent a potentially important customer segment. The analysis also points towards customers working in IT, healthcare, and aviation and purchasing across categories such as food, clothing, and electronics.

These observations can help guide further investigation into customer preferences and segment-level sales performance. However, the exact strength of these patterns should be validated against the underlying grouped sales figures before being treated as definitive conclusions.

Overall, this project demonstrates how Python-based exploratory data analysis can transform raw retail data into useful insights for understanding customer behaviour and supporting business decisions.

## 9. Business Recommendations

Based on the analysis, the following recommendations can be explored:

- **Targeted Marketing:** Develop customer campaigns tailored to age groups and other customer segments that demonstrate strong sales performance
- **Regional Campaigns:** Investigate high-performing states to identify opportunities for localised promotions
- **Product Planning:** Use product-level order rankings to inform inventory planning, while considering stock availability and profit margins
- **Customer Segmentation:** Evaluate purchasing patterns across gender, marital status, and occupation to refine campaign targeting
- **Further Analysis:** Examine profitability, average order value, repeat purchases, and campaign effectiveness if the necessary data is available

These recommendations should be tested against additional evidence before implementation

## Author

**Priyasha Soni**

Business Operations | Data Analytics | Business Intelligence

This project reflects my interest in combining analytical tools with business understanding to solve practical business problems and support data-driven decision-making.
