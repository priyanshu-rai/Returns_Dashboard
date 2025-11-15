# Sales Performance Dashboard

# Objective
This project showcases a Power BI dashboard built to analyze returns, employee performance, and Year-over-Year (YoY) trends using the Orders, People, and Returns datasets (2014–2016).
The dashboard helps identify high-return employees, track monthly trends, monitor return value changes, and support data-driven decision making.


# Datasets Used-
Orders2014.csv
Orders2015.csv
Orders2016.csv
People.xlsx
Returns.xlsx


# Data  Preparation
Cleaned and transformed all datasets in Power BI.
Ensured correct data types and created a star schema data model.
Built a Date Dimension Table using DAX (CALENDAR, YEAR, MONTH, etc.) and marked it as the official date table.
Established relationships:

Orders ↔ Returns (Order ID)

Returns ↔ People (Employee mapping)

Date ↔ Orders (Order Date)


#  DAX Measures Implemented
This project includes advanced DAX and YoY time intelligence:

Return Rate % = Number of returns / Total transactions

YoY Return Rate % Change

Avg Return Value

YoY Avg Return Value Change

Top 5 Employees by Return Count (Dynamic using RANKX)

Monthly Return Trend with YoY Overlay

Employee % Contribution to Total Returns with YoY Comparison

Time intelligence functions used:
SAMEPERIODLASTYEAR(), DATEADD(), PARALLELPERIOD()


# Key Insights

The Return Rate shows a positive YoY improvement, indicating fewer returns proportionally.

Avg Return Value increased to 1.6M, up ~64% YoY, showing that higher-value items are being returned.

Anna contributed to the highest number of returns (60%+), highlighting a potential performance or process issue.

A noticeable dip in returns during mid-2016 suggests operational improvements.


# Video Walkthrough -  https://youtu.be/vqTDmhu-45M


# 🏁 Final Outcome -

This project delivers a clear and interactive dashboard that provides management with actionable insights on returns, employee performance, and YoY trends — enabling better operational decisions.
<img width="974" height="547" alt="Snapshot_Dashboard" src="https://github.com/user-attachments/assets/d3c8c944-5b92-4418-a27f-c6f72a44376a" />
