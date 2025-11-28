# Sales Dashboard

## Table of Contents
- [Project Overview](#project-overview)
- [Tools](#tools)
- [Dashboard Development](#dashboard-development)
- [Design Highlights](#design-highlights)
- [Insights From the Dashboard](#insights-from-the-dashboard)
- [Recommendations](#recommendations)
 
## Project Overview
This project is an interactive Sales Dashboard designed to visualize key business metrics such as total sales, sales trends, customer insights, regional performance, store divisional performance and product category analysis. The goal of this dashboard is to transform raw sales data into actionable insights using Excel’s analytical features and Power Query for efficient data preparation.
It was built using Excel, and it provides a clear and insightful view of sales performance to support data-driven decision-making.

### Tools
- Microsoft Excel
- Power Query (Data Cleaning & Transformation)
- Power Pivot / Data Modeling
- Excel PivotTables & PivotCharts
- Basic DAX / Calculated Measures
- Powerpoint

### Data Cleaning & Preparation (Power Query)

I used Power Query to automate and streamline the data preparation workflow. Key steps include:

1. Data Import & Validation
-Loaded the raw dataset directly into Power Query.
   -Examined the schema to ensure proper structure.
3. Cleaning Operations
   -Removed duplicate records.
   -Corrected inconsistent entries (e.g., region names, product codes).
   -Handled missing or invalid values by removing/adjusting fields.
4. Standardization
   -Reformatted date fields (e.g., YYYY-MM-DD).
   -Converted sales values into proper number format.
   -Standardized text fields into consistent casing.
5. Feature Engineering
   -Extracted Month, Year, Quarter from transaction dates.
   -Created additional calculated fields needed for analysis (e.g., Total Sales).
6. Load to Excel
   -Loaded the cleaned dataset into the Excel data model for visualization and dashboard creation.

### Dashboard Development
After preparing the data, I built an interactive dashboard that provides:
- Key Visuals
- Total Sales KPI
- Monthly Sales Trend Chart
- Regional Performance Breakdown
- Top Products / Categories

### Design Highlights
- Clean, simple layout for decision-makers
- Dynamic slicers for region, period, or category
- Easy-to-read charts with consistent formatting

### Insights From the Dashboard
- Sales was up from the previous year
- Dhaka(Bangledesh) region generated the highest sales performance
- Beverages was the best selling product
- Customers' growth still remained stagnant

### Recommendations
- Increase marketing operations in strong regions like Dhaka and strengthen support for weaker ones such as Sylhet and Barisal
- Boost top-performing categories (Beverages, Healthy Foods) with better stocking and targeted promotions
- Review pricing strategy to address declining Average Unit Price and explore premium product options
- Promote digital payments to reduce heavy reliance on cash transactions
- Strengthen relationships with top suppliers and review low-performing ones
- Improve customer retention through loyalty programs and targeted marketing
- Use promotions and better forecasting to stabilize low-performing months
