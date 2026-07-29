# 📊 Vrinda Store Data Analysis | Excel Interactive Dashboard

An interactive **Excel Dashboard** built using **Microsoft Excel** to analyze Vrinda Store's annual sales data. This project focuses on data cleaning, preprocessing, pivot table analysis, dashboard creation, and generating business insights to support data-driven decision-making.

---

## 📌 Project Overview

The objective of this project is to transform raw sales data into meaningful insights by using Excel's analytical features such as Pivot Tables, Pivot Charts, Slicers, and formulas. The dashboard provides a clear visualization of sales performance, customer demographics, order status, and regional trends.

---

## 🎯 Objectives

- Clean and preprocess raw sales data.
- Perform sales analysis using Pivot Tables.
- Build an interactive Excel dashboard.
- Identify customer purchasing behaviour.
- Generate actionable business insights to improve sales.

---

## 🛠️ Tools & Features Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- IF Function
- TEXT Function

---

## 📂 Project Workflow

### 1️⃣ Data Cleaning

The dataset was cleaned before analysis by:

- Standardizing the **Gender** column.
- Cleaning the **Quantity (Qty)** column.
- Removing duplicate and inconsistent records.
- Ensuring data accuracy and consistency.

---

### 2️⃣ Data Processing

Additional columns were created to make the analysis easier.

#### Age Group

Customers were divided into three categories using the IF function.

```excel
=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))
```

Categories:
- Teenager
- Adult
- Senior

#### Month

A new Month column was created from the Order Date.

```excel
=TEXT(G2,"mmm")
```

For the full month name:

```excel
=TEXT(G2,"mmmm")
```

Example:

| Formula | Output |
|----------|--------|
| `mmm` | Jan |
| `mmmm` | January |

---

### 3️⃣ Data Analysis

Multiple Pivot Tables were created to analyse:

- 📈 Orders vs Sales (Monthly)
- 👨👩 Sales: Men vs Women
- 📦 Order Status Analysis
- 🏆 Top 5 States by Sales
- 👥 Orders: Age Group vs Gender

---

## 📊 Dashboard Features

The interactive dashboard includes:

- Monthly Orders vs Sales
- Sales by Gender
- Order Status Distribution
- Top 5 States by Sales
- Age Group vs Gender Analysis
- Interactive Slicers for dynamic filtering

---

## 📈 Key Insights

- 📌 Maximum sales occurred in **March**.
- 👩 Women contributed significantly more sales than men.
- 📦 Most orders were successfully delivered.
- 👩 Adult women (30–49 years) were the highest purchasing customer segment.
- 🗺️ Maharashtra, Karnataka, and Uttar Pradesh generated the highest sales.
- 🛒 Amazon, Flipkart, and Myntra were the top-performing sales channels.

---

## 💡 Business Recommendations

To improve overall sales:

- Target **women aged 30–49 years** through personalised marketing campaigns.
- Focus advertisements in **Maharashtra, Karnataka, and Uttar Pradesh**.
- Promote offers and discount coupons through **Amazon, Flipkart, and Myntra**.
- Continue improving delivery efficiency to maintain customer satisfaction.

---

## 📁 Project Structure

```
Vrinda-Store-Data-Analysis/
│
├── Vrinda Store Data.xlsx
├── Vrinda Store Dashboard.xlsx
├── Dashboard Screenshot.png
├── README.md
└── Images/
```

---

## 🚀 Future Enhancements

- Automate data cleaning using Power Query.
- Build the dashboard in Power BI.
- Add KPI cards and advanced visualisations.
- Include Year-over-Year (YoY) sales analysis.
- Add forecasting for future sales trends.

---

## ⭐ Conclusion

This project demonstrates how Microsoft Excel can be used to perform end-to-end sales analysis—from data cleaning and preprocessing to interactive dashboard creation and business insight generation. The dashboard helps stakeholders quickly understand sales trends, customer behaviour, and regional performance, enabling informed business decisions.

---

### 👨‍💻 Author

**Neeraj Kumar Verma**

⭐ **If you like this project, don't forget to star the repository!**
