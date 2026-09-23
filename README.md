# 📊 Financial Health Report -- Power BI Internship Project

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Data
Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-blue)
![Project Type](https://img.shields.io/badge/Project-Internship-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

**Financial Health Report** is an interactive **Power BI dashboard**
developed as part of my internship project.

The main purpose of this project is to transform financial data into a
clear and interactive dashboard that helps users understand important
financial indicators such as:

-   Total Revenue
-   Total Expense
-   Total Profit
-   Total EMI Amount
-   Total Pending Amount
-   Profit Margin
-   Department-wise Profit
-   Region-wise Revenue
-   Payment Status
-   Date-wise filtering

The dashboard provides a single-page view of financial performance and
allows users to interact with the report using slicers and Power BI
visualizations.

------------------------------------------------------------------------

## 🎯 Project Objectives

The major objectives of this project are:

1.  Analyze financial data using Power BI.
2.  Create meaningful KPIs for financial performance.
3.  Compare revenue, expense, and profit.
4.  Analyze profit across different departments.
5.  Analyze revenue across different regions.
6.  Track EMI and payment status.
7.  Identify pending financial amounts.
8.  Provide interactive filtering using slicers.
9.  Present business information through easy-to-understand
    visualizations.
10. Build an internship-level business intelligence dashboard.

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

  -----------------------------------------------------------------------
  Tool / Technology                   Purpose
  ----------------------------------- -----------------------------------
  **Microsoft Power BI**              Dashboard development and data
                                      visualization

  **Power Query**                     Data cleaning and transformation

  **DAX**                             Measures and financial calculations

  **Excel / Dataset**                 Source financial data

  **GitHub**                          Project documentation and version
                                      control
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 📊 Dashboard Preview

> Add your Power BI dashboard screenshot to the repository with the
> filename `dashboard.png`.

``` text
dashboard.png
```

You can then display it in GitHub by adding:

``` markdown
![Financial Health Report Dashboard](dashboard.png)
```

------------------------------------------------------------------------

## 📈 Key Performance Indicators (KPIs)

The dashboard contains the following major KPIs:

### 1. Total Revenue

Shows the total revenue generated from the available financial records.

### 2. Total Expense

Shows the total expenses recorded in the dataset.

### 3. Total Profit

Represents the difference between revenue and expense.

**Formula:**

``` text
Profit = Revenue - Expense
```

### 4. Total EMI Amount

Shows the total EMI amount available in the financial data.

### 5. Total Pending Amount

Shows the amount that is still pending according to the payment records.

### 6. Profit Margin

Shows profitability as a percentage of revenue.

A common calculation is:

``` text
Profit Margin % = (Profit / Revenue) × 100
```

------------------------------------------------------------------------

## 📊 Dashboard Visualizations

The report contains multiple visualizations to analyze financial
performance.

### 🔹 Sum of Expense by Revenue

A column chart used to compare expense values against revenue values.

### 🔹 Sum of Profit by Department

Shows how profit is distributed across departments such as:

-   Marketing
-   HR
-   Other departments available in the dataset

### 🔹 Sum of Revenue by Region

A doughnut chart showing the contribution of different regions.

The dashboard screenshot includes regions such as:

-   West
-   South

### 🔹 EMI Amount by Payment Status

A doughnut chart used to compare EMI amounts based on payment status:

-   Paid
-   Pending

### 🔹 Profit Margin

A visual representation of profit-margin-related information.

------------------------------------------------------------------------

## 🎛️ Interactive Filters / Slicers

The dashboard uses interactive slicers to allow users to filter the
report.

### Date Slicer

Users can select a particular date or date range.

### Department Slicer

Users can filter the dashboard according to department.

When a slicer is changed, the related dashboard visuals and KPI values
update according to the selected filter context.

------------------------------------------------------------------------

## 🧮 DAX Measures

Some example DAX measures used for the dashboard are:

### Total Revenue

``` dax
Total Revenue =
SUM('Financial Data'[Revenue])
```

### Total Expense

``` dax
Total Expense =
SUM('Financial Data'[Expense])
```

### Total Profit

``` dax
Total Profit =
[Total Revenue] - [Total Expense]
```

### Profit Margin

``` dax
Profit Margin % =
DIVIDE([Total Profit], [Total Revenue], 0) * 100
```

> **Note:** Column/table names should be changed if your actual dataset
> uses different names.

------------------------------------------------------------------------

## 🔄 Project Workflow

The project was developed using the following workflow:

``` text
Raw Financial Data
        ↓
Data Import
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Dashboard Design
        ↓
Interactive Slicers
        ↓
Financial Analysis
        ↓
Final Power BI Report
```

------------------------------------------------------------------------

## 🧹 Data Cleaning & Transformation

Before creating the dashboard, the financial dataset can be prepared
using **Power Query**.

Typical data-preparation activities include:

-   Removing duplicate records
-   Handling missing values
-   Correcting data types
-   Formatting date columns
-   Cleaning department names
-   Cleaning region names
-   Checking payment-status values
-   Checking numerical columns
-   Creating required calculated columns

------------------------------------------------------------------------

## 📌 Example Dashboard Values

The uploaded dashboard screenshot currently shows approximately:

  KPI                       Value
  ---------------------- --------
  Total Revenue            41.55K
  Total Expense            22.62K
  Total Profit             18.92K
  Total EMI Amount         96.62K
  Total Pending Amount     11.60K

These values represent the current filtered dashboard view and may
change when slicers or filters are applied.

------------------------------------------------------------------------

## 💡 Business Questions Answered

This dashboard can help answer questions such as:

-   What is the total revenue?
-   How much expense has been recorded?
-   What is the total profit?
-   What is the profit margin?
-   Which department contributes to profit?
-   How is revenue distributed across regions?
-   How much EMI is paid?
-   How much EMI is pending?
-   How do financial KPIs change for a selected date?
-   How do financial results change for a selected department?

------------------------------------------------------------------------

## 📂 Suggested GitHub Repository Structure

``` text
Financial-Health-Report/
│
├── README.md
├── dashboard.png
│
├── PowerBI/
│   └── Financial_Health_Report.pbix
│
├── Dataset/
│   └── Financial_Data.xlsx
│
└── Documentation/
    └── Project_Report.pdf
```

> If the original dataset or PBIX file is confidential, do not upload it
> publicly. Upload only files that you are permitted to share.

------------------------------------------------------------------------

## 🚀 How to Use the Project

1.  Download or clone the repository.
2.  Open the `.pbix` file using Microsoft Power BI Desktop.
3.  Check the data source.
4.  Refresh the dataset if required.
5.  Use the **Date** slicer to filter the report.
6.  Use the **Department** slicer to analyze individual departments.
7.  Interact with the charts to explore financial performance.

------------------------------------------------------------------------

## 📊 Sample Analysis from the Dashboard

The dashboard provides a high-level financial overview. In the displayed
view, revenue, expense, profit, EMI, and pending amounts are presented
as KPI cards.

Department and region visuals provide additional breakdowns, while
payment-status analysis helps distinguish between paid and pending
amounts.

Because the report is interactive, the displayed values can change based
on the selected date, department, or other filter context.

------------------------------------------------------------------------

## 🎓 Internship Learning Outcomes

Through this project, I gained practical experience in:

-   Power BI dashboard development
-   Data cleaning using Power Query
-   Data visualization
-   DAX calculations
-   KPI creation
-   Slicers and filters
-   Interactive dashboard design
-   Business-oriented data analysis
-   Financial data interpretation
-   Report presentation
-   GitHub project documentation

------------------------------------------------------------------------

## 🔮 Future Enhancements

The project can be improved further by adding:

-   Monthly revenue and expense trends
-   Year-over-year financial comparison
-   Budget vs actual analysis
-   Department-wise expense analysis
-   More detailed cash-flow analysis
-   Financial risk indicators
-   Drill-through pages
-   Dashboard navigation buttons
-   Tooltip pages
-   Automated data refresh
-   More advanced DAX measures
-   Mobile-optimized Power BI layout

------------------------------------------------------------------------

## 🏆 Project Highlights

### Dashboard Features

-   ✅ Interactive Power BI dashboard
-   ✅ KPI cards
-   ✅ Department analysis
-   ✅ Region analysis
-   ✅ Payment-status analysis
-   ✅ EMI analysis
-   ✅ Profit analysis
-   ✅ Date filtering
-   ✅ Department filtering
-   ✅ DAX-based calculations
-   ✅ Business-focused visualizations

------------------------------------------------------------------------

## 👨‍💻 Author

**Shivam Parmar**

**Role:** BCA Student / Data Analytics Intern

**Skills demonstrated in this project:**

`Power BI` • `Power Query` • `DAX` • `Data Analysis` •
`Data Visualization` • `Excel`

------------------------------------------------------------------------

## 📜 Project Type

**Internship Project -- Financial Health Report**

This project was created for learning and practical experience in **Data
Analytics and Business Intelligence using Microsoft Power BI**.

------------------------------------------------------------------------

## ⭐ If You Like This Project

If this project is useful, you can:

-   ⭐ Star the repository
-   🍴 Fork the repository
-   💬 Share feedback
-   📌 Use it as a reference for Power BI learning

------------------------------------------------------------------------

## 📬 Contact

For questions or collaboration, connect with me through GitHub or
LinkedIn.

**Thank you for visiting this project!**
