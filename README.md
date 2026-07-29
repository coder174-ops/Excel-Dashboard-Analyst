## Excel- Vrinda Store Data Analysis
📌 Project Overview

This project analyzes Vrinda Store's sales data using Microsoft Excel to identify customer purchasing patterns, sales trends, and business insights. The project includes data cleaning, data processing, pivot table analysis, interactive dashboard creation, and actionable recommendations to improve sales.

🎯 Objectives
Clean and preprocess raw sales data.
Create interactive Excel dashboards using Pivot Tables and Charts.
Analyze customer demographics and sales performance.
Generate business insights to support decision-making.
🛠️ Tools Used
Microsoft Excel
Pivot Tables
Pivot Charts
Slicers
Conditional Formatting
Excel Functions (IF, TEXT)
📂 Project Workflow
1. Data Cleaning

Performed data cleaning to improve data quality.

Tasks:

Cleaned the Gender column (removed inconsistencies).
Corrected the Quantity (Qty) column.
Removed duplicate and invalid records.
Standardized the dataset.
2. Data Processing

Created additional columns for better analysis.

Age Group Column

Used nested IF formula to categorize customers into age groups.

=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))

Age Categories:

Teenager
Adult
Senior
Month Column

Extracted month names from the order date.

=TEXT(G2,"mmm")

For full month name:

=TEXT(G2,"mmmm")

Example:

mmm → Jan, Feb, Mar
mmmm → January, February, March
3. Data Analysis

Created Pivot Tables for the following analyses:

A. Orders vs Sales
Compared total orders and sales month-wise.
B. Sales by Gender
Compared purchases made by Men and Women.
C. Order Status

Analyzed order completion percentage:

Delivered
Refunded
Returned
Cancelled
D. Top 5 States by Sales

Identified states contributing the highest revenue.

E. Orders by Age Group vs Gender

Analyzed customer purchasing behavior across different age groups and genders.

📊 Dashboard Components

The interactive dashboard includes:

Monthly Orders vs Sales
Sales by Gender
Order Status Distribution
Top 5 States by Sales
Orders by Age Group and Gender
Interactive Slicers (Month, Channel, Category)
📈 Key Insights
Maximum sales were recorded in March.
Women contributed significantly more purchases than men.
Most orders were successfully delivered.
Adult women (30–49 years) made the highest number of purchases.
Maharashtra, Karnataka, and Uttar Pradesh generated the highest sales.
Amazon, Flipkart, and Myntra were the top-performing sales channels.
💡 Business Recommendations

To improve Vrinda Store sales:

Focus marketing campaigns on women aged 30–49 years.
Target customers in Maharashtra, Karnataka, and Uttar Pradesh.
Offer discounts and promotional coupons through Amazon, Flipkart, and Myntra.
Continue improving delivery success rates to enhance customer satisfaction.
📌 Project Outcome

The dashboard enables stakeholders to:

Monitor sales performance interactively.
Understand customer purchasing behavior.
Identify top-performing regions and sales channels.
Make data-driven business decisions.
