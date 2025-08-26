# Adventure-Works   ![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Viz-yellow?logo=powerbi)

## 1. Adventure Works: Global Sales & Performance Dashboard
A dynamic Power BI dashboard analyzing revenue, budget variances, and product trends across regions and time periods—designed for data-driven decision-making.

## 2. Short Description
The Adventure Works Dashboard is an interactive Power BI report that transforms raw sales data into actionable insights. It compares actual sales against budgets, identifies top-performing products and customers, and uncovers regional trends. Built for sales managers, financial analysts, and executives, this tool answers critical questions like:

  * Which products drive the most revenue?
  * Where are we exceeding or falling short of budget?
  * How do sales trends vary by region or season?

## 3. Tech Stack
📊 Power BI Desktop: Primary platform for visualization and report design.

🔧 Power Query: Cleaned and reshaped data (e.g., unpivoted budget tables, standardized dates).

🧮 DAX: Measures like Sales Variance %, YTD(Yead-To-Date) Growth, and dynamic rankings.

🔗 Data Modeling: Star schema with relationships between Sales, Products, Territories, and Calendar tables.

📁 File Formats: .pbix (Power BI project) + .png (dashboard previews).

## 4. Data Source

Source: Microsoft’s Adventure Works sample database (fictional but realistic retail data).
  
Datasets:
  * Sales: 60K+ transactions (2016–2017) with revenue, quantities, and order dates.
  * Products: 500+ items with categories, subcategories, and pricing tiers.
  * Budget: Monthly targets by product and region.
  * Calendar: Time intelligence for YoY and MoM comparisons.

## 5. Key Features & Insights

### 5.1 Business Problem
Adventure Works lacks a unified view of:
* Real-time sales vs. budget performance.
* Regional profitability and product trends.
* Seasonal patterns affecting inventory and staffing.
        
### 5.2 Dashboard Goals
* Provide at-a-glance KPIs (revenue, variance, top products).
* Enable drill-down analysis by region, time, or product category.
* Highlight anomalies (e.g., underperforming regions).
        
### 5.3 Walkthrough of Key Visuals
📊 Key Metrics (Cards)
   * Total Sales: $29M | Budget Variance: -$1.2M (4% under)
   * Top Category: Bikes (62% of revenue) | Best Region: North America ($12M)
          
🌍 Sales by Region (Map + Bar Chart)
   * Interactive map color-coded by revenue.
   * Bar chart ranks territories (e.g., North America > Europe > Pacific).
          
📈 Monthly Sales vs. Budget (Line + Column Chart)
  * Columns: Actual sales. Line: Budget targets.
  * Red highlights show months below target.
          
🏆 Top 10 Products & Customers (Tables)
   * Filter by category (e.g., Mountain Bikes generate 35% of revenue).
          
⏳ Time Intelligence (Slicers)
   * Compare YTD, QTD(Quarter-To-Date), or custom date ranges.
          
### 5.4 Business Impact
* Cost Control: Immediate visibility into budget deviations.
* Inventory Optimization: Focus procurement on top-selling products (e.g., Road Bikes in Q2).
* Strategic Growth: Allocate marketing spend to underperforming regions (e.g., APAC).

## 6. Screenshot Preview

![Dashboard Preview](https://github.com/nitikad58/Adventure-Works/blob/607faeb91d0bd9895c6f1892e079403d9dd08758/Screenshot%20of%20Adventure%20Works.png)
