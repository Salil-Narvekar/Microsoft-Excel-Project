**Microsoft Excel Project - Data Analysis of a Clothing Stores Sales**
    This project demonstrates end-to-end data analysis and visualization using Microsoft Excel, focusing on retail clothing sales data. The workflow includes data cleaning, transformation, KPI generation, and dashboard visualization to derive actionable business insights.

**Problem Statement:** 
    To imporve the annual years sales of the upcomming year by understanding the underline patterns from the objectives and providing the insights

**End User:**
    Sales department of the CLothing store itself

**Project Workflow:**
1. Raw Dataset Import & Inspection
- Initial dataset contained inconsistencies such as:
- Null values in columns (e.g., City).
- Inconsistent categorical entries (e.g., "mAle", "male", "femal").
- Incorrect data types (e.g., Quantity Sold stored as text).

2. Fields included:
- Order ID, Customer Name, Gender, Age, City, Order Date, Clothing Type, Clothing Size, Quantity Sold, Unit Price, Payment Mode.

3. Data Cleaning & Transformation
- Standardized categorical data (Gender, Clothing Size, City).
- Converted Quantity Sold into numeric for correct aggregation.

4. Derived new calculated fields:
- Total Price = Quantity Sold × Unit Price.
- Discount (10%) applied on eligible orders.
- Total Payable Amount = Total Price – Discount.
- Added Order Season classification based on Order Date, Extracting the months from it and assigning the Seasons based upon the month number using the IF Statement.

5. KPI Development
Created Key Performance Indicators including:
a. Total Sales.
b. Total Orders.
c. Total Quantity Sold.

6. Data Analysis Sheets:
a. Size Demand Analysis – Identified most purchased clothing sizes.
b. Seasonal Trend Analysis – Compared performance across Rainy/Winter seasons.
c. Regional Performance – Mapped city-wise contribution.
d. Item Sales Analysis – Tracked category-level sales insights.

7. Dashboards & Visualization
- Developed interactive dashboards using:
Pivot Tables & Pivot Charts.
Conditional Formatting.
Slicers for dynamic filtering.

8. Tools & Techniques Used
- Data Cleaning & Transformation (Text functions, Date functions).
- Pivot Tables & Pivot Charts for aggregations.
- Lookup Functions (VLOOKUP/XLOOKUP).
- Conditional Formatting for data highlighting.
- Dashboard Designing with slicers and charts.
- Dashboards provided a consolidated view of KPIs for better decision-making.

**Conclusion:**
- Built a clean, structured dataset ready for analysis.
- Automated KPI calculations for business decision-making.
- Delivered interactive dashboards for insights on customer behavior, product demand, seasonal impact, and revenue performance.Built a clean, structured dataset ready for analysis.
- Automated KPI calculations for business decision-making.
- Delivered interactive dashboards for insights on customer behavior, product demand, seasonal impact, and revenue performance.
