# Blinkit-Analytics-Quick-Commerce-Performance-Dashboard
🛒 Blinkit Analytics: Quick Commerce Performance Dashboard

2. Short Description / Purpose

The Blinkit Analytics Dashboard is an interactive Power BI report designed to help stakeholders monitor and analyze quick-commerce operations across customers, inventory, products, orders, and marketing performance in a single consolidated view. This tool is intended for operations analysts, category managers, and business decision-makers who need a quick, data-driven read on sales performance, inventory health, and marketing ROI.

3. Tech Stack
The dashboard was built using the following tools and technologies:
📊 Power BI Desktop – Main data visualization and report-building platform.
📂 Power Query – Data cleaning and transformation layer for shaping raw Blinkit datasets (customers, inventory, products, orders, marketing performance) into analysis-ready tables.
🧠 DAX (Data Analysis Expressions) – Used for calculated measures such as [total revenue, average order value, inventory turnover ,Payment Methods , Average ROAS ,Total cost , Total Damage etc ]
📝 Data Modeling – Star-schema relationships built across customers, orders, products, inventory, and marketing tables to enable cross-filtering and aggregation.
📁 File Format – .pbix for development and .png for dashboard previews.


4. Data Source
Source:Kaggle
The data spans five interconnected tables — customers, inventory, products, orders, and marketing performance — covering customer demographics, product catalog details, stock levels, order transactions, and campaign-level marketing metrics.

5. Features / Highlights
Business Problem
Quick-commerce platforms like Blinkit operate on thin margins and rapid inventory turnover, making it difficult for teams to quickly answer questions like: Which products and categories drive the most revenue? Where are stockouts or overstock situations occurring? Which customer segments are most valuable? Is marketing spend translating into orders?

6.Goal of the Dashboard
To deliver a 3-page interactive report — Executive Overview, Sales, and Marketing — that:
Enables stakeholders to monitor sales, inventory, and marketing performance at a glance.
Supports decisions such as restocking priorities, campaign budget allocation, and customer targeting.
Surfaces trends across product categories, order patterns, and customer behavior.


Walkthrough of Key Visuals
(Fill in with your actual dashboard elements — placeholders below based on typical Blinkit-style datasets)

Page 1 — Executive Overview
Key KPIs (Top Row): Total revenue, total orders, average order value, active customers, [inventory fill rate]
Filter Panel: Interactive slicers to filter all visuals by category, region, or time period.
Revenue Trend (Line Chart): Displays revenue/order volume over time to identify peak periods.
Revenue by Category (Bar Chart): Ranks product categories by sales contribution.


Page 2 — Sales
Sales KPIs: [Total sales, units sold, average order value, top-selling SKUs]
Revenue by Category/Product (Bar Chart): Breaks down sales performance by category or product.
Inventory Health (Table/Matrix): Highlights low-stock or overstocked SKUs alongside sales velocity.
Order Trends (Line Chart): Order volume over time, by region or category.


Page 3 — Marketing
Marketing KPIs: [Spend, impressions, conversions, ROI/ROAS]
Marketing Performance (Stacked Bar/Card visuals): Compares spend vs. orders generated across campaigns or channels.
Customer Segmentation (Donut/Bar Chart): Breaks down customers by [frequency, region, or value tier] to show campaign targeting effectiveness.


Business Impact & Insights
Inventory Optimization: Ops teams can quickly spot stockouts or excess inventory and act before it affects sales.
Marketing Efficiency: Marketing teams can reallocate budget toward higher-performing campaigns.
Revenue Growth: Category managers can identify top-performing and underperforming product lines.
Customer Insights: Business teams can tailor retention strategies based on customer segment behavior.


6. Screenshots / Demos
https://github.com/chentsa/Blinkit-Analytics-Quick-Commerce-Performance-Dashboard/blob/main/executive%20overview.png
https://github.com/chentsa/Blinkit-Analytics-Quick-Commerce-Performance-Dashboard/blob/main/Sales%20analysis.png
https://github.com/chentsa/Blinkit-Analytics-Quick-Commerce-Performance-Dashboard/blob/main/executive%20overview.png
