# Budget vs Actual Financial Analysis (Excel Project)
## Project Overview
.This project focuses on analyzing organizational spending by comparing budgeted amounts with actual expenditures across different departments, regions, and categories.
The goal is to identify patterns, detect overspending or underspending, and provide insights that can support better financial decision-making.

### Objectives
1. Compare Budget vs Actual spending
2. Identify overspending and underspending trends
3. Analyze regional and departmental performance
4. Determine major cost drivers
5. Evaluate payment method usage
6. Examine monthly spending trends
### Dataset Description
The dataset contains the following fields:
 .Date
 .Department
 .Category
 .Region
 .Budget Amount
 .Actual Amount
 .Payment Method
 .Transaction ID
 ###Additional columns created:
 .Variance (Actual - Budget)
 .Performance Status (Overspending / Underspending)
 .Month (for trend analysis)
### Data Cleaning Process
      Data cleaning was performed using Power Query and Excel, including:
       .Replaced missing values in Region and Department with "Unknown"
       .Ensured correct data types (Date, Numeric, Text)
       .Removed duplicates using Transaction ID
 Created calculated columns using Excel formulas:
     .Variance
     .Performance Status
Structured the dataset into an Excel Table for efficient analysis

### Exploratory Data Analysis (EDA)
  EDA was carried out using:
     .Pivot Tables
     .Charts (Column, Bar, Pie, Line)

## Business Questions & Insights
### 1. How does actual spending compare to budget across departments?
       .Most departments recorded higher actual spending than budget, indicating overspending.
       .The Unknown department showed underspending, suggesting incomplete classification of some transactions.
### 2. Which regions have the highest and lowest spending variance?
        .Certain regions recorded high positive variance, indicating overspending.
        .Other regions showed better budget control with lower or negative variance.
### 3. Which expense categories consume the most budget?
        .Some categories (e.g., Salaries / Operations) accounted for the largest share of total spending.
        .These categories represent the major cost drivers of the organization.
### 4. What is the most frequently used payment method?
        .Bank Transfer / Digital payments were the most commonly used methods.
        .This indicates a preference for cashless transactions.
### 5 How does spending change over time?
        .Spending trends showed fluctuations across months.
        .Certain months recorded peak expenditures, indicating periods of increased financial activity.

## Tools Used
     .Microsoft Excel
     .Power Query
     .Pivot Tables
     .Data Visualization (Charts)

## Key Insights
     .There is a consistent pattern of overspending across most departments.
     .Budget planning may need to be reviewed for accuracy.
     .A few missing classifications (Unknown category) may affect precision.
     .Major expenses are concentrated in a few categories.
     .Digital payment methods dominate transactions.
## Conclusion
This analysis highlights gaps between planned and actual spending and provides insights that can help improve budgeting, cost control, and financial planning within an organization.

## Author
Achilaka Msendoo Francisca

Data Analyst (Entry-Level)
Skilled in Excel, Data Cleaning, and Visualization



