🛒 E-Commerce Sales Overview Dashboard (Excel)
📌 Project Overview

The E-Commerce Sales Overview Dashboard is an interactive Excel-based analytics dashboard designed to track, visualize, and interpret key sales and profit performance indicators for an international retail business. It provides an end-to-end view of total revenue, profitability, and sales distribution across customer segments, regions, and product categories.

The project demonstrates advanced Excel skills in data cleaning, aggregation, visualization, and interactivity using Pivot Tables, Pivot Charts, and Slicers.
<img width="1151" height="669" alt="Screenshot 2025-10-19 171556" src="https://github.com/user-attachments/assets/21dab87f-eb26-44f4-87ac-836f59320843" />

🎯 Objectives

To analyze overall sales, profits, and order quantities across time periods.

To identify top-performing regions, countries, and categories contributing to revenue.

To examine customer-segment profitability and shipping performance.

To build a visually appealing, interactive dashboard for managerial insights.

🧾 Dataset Description

The dataset contains transactional-level sales and profit details from a global e-commerce business.

Column Name	Description
Order ID	Unique identifier for each order
Order Date	Date on which the order was placed
Ship Date	Date of shipment
Customer Name	Name of the customer
Segment	Market segment (Consumer, Corporate, Home Office)
Country	Country where the order was placed
Region	Market region (USCA, LATAM, Europe, etc.)
Category	Product category (e.g., Cardio Equipment, Fishing, etc.)
Sub-Category	Specific product line
Sales	Total revenue generated per order
Profit	Profit earned per order
Quantity	Number of units sold
Shipping Mode	Shipping type (First Class, Second Class, Standard Class, Same Day)
Order Status	Current order state (Completed, Pending, Cancelled, etc.)
⚙️ Data Preparation

The raw dataset underwent data cleaning, standardization, and transformation in Excel before dashboard development.

🧹 Data Cleaning Steps

Checked and reformatted all date fields to proper Excel Date format.

Removed duplicate and blank rows to ensure data integrity.

Standardized categorical values for Customer Segment, Shipping Mode, and Order Status.

Created a dynamic Excel table (Ctrl + T) to automatically refresh pivot data.

🧮 Feature Engineering

Created calculated fields for:

Total Sales

Total Profit

Profit Margin (%) = (Profit / Sales) * 100

Order Quantity

Extracted Year and Quarter from Order Date for time-based analysis.

Aggregated data for regional and category-level summaries using Pivot Tables.

📊 Dashboard Components

The Excel dashboard is designed for executive-level insight and interactivity.

1️⃣ KPI Summary Cards
Metric	Description
💰 Total Sales	$26,474,659
💵 Total Profit	$2,495,874
📦 Total Order Quantity	284,209 units
📈 Average Profit Margin	10.86%

These KPIs provide a quick snapshot of the business’s overall financial performance.

2️⃣ Monthly Sales Trend

A line chart visualizing monthly total sales for the analysis period (2016–2017).

Highlights stable monthly revenue between $1.5M–$2.0M with minor seasonal dips.

3️⃣ Sales by Market Region

A pie chart showing revenue distribution by global market regions:

Europe: 25%

LATAM: 24%

Pacific Asia: 22%

USCA: 20%

Africa: 9%

Indicates strong market presence across multiple regions with balanced revenue share.

4️⃣ Sales by Customer Segment

Bar chart comparing Consumer ($13.85M), Corporate ($7.84M), and Home Office ($4.78M) segments.

Consumer segment leads with over 50% of total revenue.

5️⃣ Top 10 Countries by Sales

Treemap visualization displaying country-wise contribution:

United States ($3.71M), France ($2.06M), Germany ($1.45M), Brazil ($1.21M), etc.

Helps identify high-performing geographic markets.

6️⃣ Top 5 Categories by Sales

Horizontal bar chart of best-selling product categories:

Cardio Equipment – $4.66M

Fishing – $4.25M

Camping & Hiking – $3.03M

Cleats – $2.70M

Water Sports – $2.37M

7️⃣ Bottom 5 Categories by Sales

Highlights underperforming segments such as:

Baby Products ($1.40K)

Golf Bags & Carts ($8.96K)

Video Games ($8.63K)

CDs ($2.88K)

Toys ($2.75K)

Useful for identifying categories requiring marketing or pricing interventions.

8️⃣ Filter Panel

Interactive slicers allow users to dynamically filter insights by:

Order Date (Year/Quarter)

Customer Segment

Shipping Mode

Order Status

This enables real-time, multi-dimensional exploration of business performance.

📈 Key Insights

Europe and LATAM are the top-performing regions, contributing nearly half of total revenue.

Consumer Segment dominates total sales, indicating strong B2C performance.

Profit margin is healthy at 10.86%, reflecting balanced pricing and cost management.

Cardio Equipment and Fishing categories lead in sales volume and profitability.

Underperforming product lines (Baby, CDs, Toys) offer scope for re-strategizing or discontinuation.

🧠 Business Recommendations

Increase marketing efforts in high-margin categories (Cardio Equipment, Fishing).

Reassess or phase out low-revenue categories to optimize inventory.

Expand Consumer-segment campaigns in Europe and LATAM.

Promote First-Class and Same-Day Shipping as premium delivery options to enhance customer satisfaction.

Integrate forecasting models in future versions to predict monthly sales trends.

🛠️ Tools & Techniques
Tool	Purpose
Microsoft Excel	Dashboard creation and analysis
Pivot Tables & Pivot Charts	Aggregation and dynamic visualizations
Slicers & Timelines	Interactive filtering
Data Tables	Auto-refresh data source
Conditional Formatting	Enhanced visual emphasis on KPIs
🧩 Skills Demonstrated

Data cleaning and preparation in Excel

Business KPI development and aggregation

Dashboard visualization using Pivot Charts

Analytical storytelling and performance insight generation

Interactive dashboard design for executives

📁 Deliverables

Excel File: Ecommerce Dashboard.xlsx

Dashboard Preview:


🚀 Future Enhancements

Connect to live data sources (CSV/API/SQL).

Add product-level drill-downs with Power Query.

Implement forecasting models using Excel’s Data Analysis ToolPak.

Create a Power BI version for enterprise scalability.

👨‍💻 Author

Puneeth Vijay Krishna Samarla
M.S. in Information Science (Machine Learning), University of Arizona
📧 puneethsamarla@email.com

🔗 LinkedIn
