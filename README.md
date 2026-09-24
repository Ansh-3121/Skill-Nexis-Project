# Global Superstore Sales Analysis Dashboard

## Project Overview
This project is an Excel-based Pivot Table Dashboard that analyzes sales data 
from a Global Superstore. The goal is to understand business performance by 
revenue, category, year, and department.

## Dataset
The Excel file has 3 sheets:
- Orders – Main sales data (Order ID, Date, Category, Segment, Sales, Quantity, 
  Discount, Region, etc.) — this sheet was used for the analysis
- Returns – List of returned orders (not used directly in this project)
- People – List of region-wise responsible person (not used directly in this project)

## Tools Used
- Microsoft Excel
- Pivot Tables and Pivot Charts
- Excel Formulas

## Steps I Did
1. Studied and understood the Orders sheet data
2. Added a new Revenue column using this formula:
   Revenue = Sales x Quantity x (1 - Discount)
3. Created Pivot Tables and turned them into charts:
   - Total Revenue – Overall revenue from all data
   - Sales by Category – Percentage split of Furniture, Office Supplies, and Technology (Pie Chart)
   - Yearly Sales Trends – Sales growth from 2012 to 2015 (Bar Chart with trendline)
   - Department-wise Revenue – Revenue split by Consumer, Corporate, and Home Office (Bar Chart)
4. Arranged all charts together on one Dashboard sheet
5. Added currency ($) formatting to make it look clean and professional

## Key Insights
- Total Revenue: 5,52,06,237.67 dollars
- Technology category brings in the most revenue (38 percent)
- Sales have grown steadily from 2012 to 2015
- Consumer segment brings in the most revenue, followed by Corporate and Home Office

## File
- internship_project.xlsx — Full workbook with Orders data, Pivot Tables, and Dashboard
