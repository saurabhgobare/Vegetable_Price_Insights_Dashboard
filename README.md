## Vegetable Price Insights Dashboard | Vegetable Market Analysis

# Project Overview
The Vegetable Price Insights Dashboard is a Power BI project designed to track, visualize, and analyze vegetable prices in relation to weather patterns such as temperature and rainfall. It helps users understand price fluctuations, compare prices over time, and monitor trends for different vegetables. This dashboard provides actionable insights for farmers, vendors, and market analysts.

# Dataset
•	Source: Kaggle (Vegetable Price & Weather dataset)
•	Columns:
1.	Date – Daily recorded date
2.	Avg Temperature (°C) – Daily average temperature
3.	Rainfall (mm) – Daily rainfall
4.	Item Price (₹/kg) – Vegetable price per kilogram
•	Cleaning: Removed duplicate rows where the same item, same day, and same price were repeated. Handled minor missing values and formatted the date column for time-series analysis.

# Dashboard Components
1.	Price Trend vs Rainfall (Area Chart)
o	Shows how vegetable prices fluctuate with rainfall patterns.
2.	Price Trend vs Temperature (Area Chart)
o	Shows how vegetable prices vary with temperature changes.
3.	Item-wise Monthly Price Range (Stacked Column Chart)
o	Displays monthly price ranges for the selected vegetable using the slicer.
4.	KPI Cards
o	Minimum & Maximum Price – Quick overview of price extremes.
o	Minimum & Maximum Avg Temperature – Overview of weather conditions.
o	Minimum & Maximum Rainfall – Overview of rainfall patterns.
5.	Gauge Chart
o	Shows Min, Max, and Average Price dynamically based on the selected vegetable.
6.	Item Slicer
o	Allows selection of specific vegetables to filter all visuals dynamically.
7.	Drill-through: Item Price Analysis
o	Enables deep-dive analysis for the selected vegetable, displaying monthly price trends and average prices.

# Key Features
•	Interactive item slicer for dynamic filtering of visuals.
•	Trend analysis of price vs weather parameters (rainfall & temperature).
•	KPIs for quick assessment of price extremes.
•	Gauge for dynamic min, max, and average price per item.
•	Drill-through functionality for deeper item-level price insights.
•	Simple, clear, and intuitive visualizations for market decision-making.

# Insights
•	High rainfall and extreme temperatures can lead to price spikes for certain vegetables.
•	Seasonal variations affect the supply-demand cycle, influencing price trends.
•	Monitoring specific vegetables helps identify critical periods for price changes.
•	Correlations between weather and prices can assist farmers and vendors in planning.
•	Item-wise drill-through allows a detailed view of monthly price fluctuations.

# Potential Enhancements
•	Add forecasting models to predict future vegetable prices.
•	Include year-wise comparisons for long-term trend analysis.
•	Integrate geographic analysis to study region-wise price differences.
•	Add interactive tooltips with detailed insights per vegetable or month.
•	Enable export of filtered reports for sharing with stakeholders.

# Tools Used
•	Power BI Desktop – For interactive dashboard creation
•	Excel – For data storage, cleaning, and preparation

# Dashboard Preview


# How to Use
1.	Open the Power BI dashboard file (Vegetable Market Analysis.pbix).
2.	Use the Item Slicer to select the vegetable of interest.
3.	Hover over charts to view detailed information and insights.
4.	Monitor KPI Cards and Gauge Charts for quick assessment of price patterns.
5.	Use Drill-through to explore monthly price trends for the selected vegetable.

