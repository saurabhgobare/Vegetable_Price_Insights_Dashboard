# Vegetable Price Insights Dashboard | Vegetable Market Analysis



### Project Overview
The **Vegetable Price Insights Dashboard** is an **interactive Power BI project** designed to track, visualize, and analyze **vegetable prices** in relation to **weather patterns** such as temperature and rainfall.

It helps users:  
- **Understand price fluctuations**  
- **Compare vegetable prices over time**  
- **Monitor trends for different vegetables**  

This dashboard provides **actionable insights** for **farmers, vendors, and market analysts**.



### Dataset
- **Source**: **Kaggle (`Vegetable Price & Weather dataset`)**  

- **Columns**:  
  - **Date** → `Daily recorded date`  
  - **Avg Temperature (°C)** → `Daily average temperature`  
  - **Rainfall (mm)** → `Daily rainfall`  
  - **Item Price (₹/kg)** → `Vegetable price per kilogram`  

- **Cleaning**:  
  - **Removed duplicate rows** where the same item, same day, and same price were repeated  
  - **Handled minor missing values**  
  - **Formatted the `Date` column** for **time-series analysis**



### Dashboard Components
- **Price Trend vs Rainfall (Area Chart)** → **Shows how vegetable prices fluctuate with rainfall patterns**  
- **Price Trend vs Temperature (Area Chart)** → **Shows how vegetable prices vary with temperature changes**  
- **Item-wise Monthly Price Range (Stacked Column Chart)** → **Displays monthly price ranges for the selected vegetable**  
- **KPI Cards**:  
  - **Minimum & Maximum Price** → **Quick overview of price extremes**  
  - **Minimum & Maximum Avg Temperature** → **Weather overview**  
  - **Minimum & Maximum Rainfall** → **Rainfall overview**  
- **Gauge Chart** → **Shows Min, Max, and Average Price dynamically based on the selected vegetable**  
- **Item Slicer** → **Filter all visuals by specific vegetables dynamically**  
- **Drill-through: Item Price Analysis** → **Deep-dive for the selected vegetable with monthly price trends**



### Key Features
- **Interactive Item Slicer** for dynamic filtering  
- **Trend analysis of price vs weather parameters** (`rainfall & temperature`)  
- **KPI Cards** for quick assessment of price extremes  
- **Gauge chart** for dynamic **Min, Max & Average price**  
- **Drill-through functionality** for detailed item-level price insights  
- **Clean, intuitive visualizations** for market decision-making



### Business Insights
- **Weather Impact** → **High rainfall & extreme temperatures can lead to price spikes**  
- **Seasonality** → **Seasonal variations affect supply-demand cycles and price trends**  
- **Critical Periods** → **Monitoring specific vegetables identifies periods of rapid price change**  
- **Correlation Analysis** → **Price vs weather insights help farmers & vendors plan supply**  
- **Item-wise Drill-through** → **Detailed monthly price fluctuations per vegetable**



### Potential Enhancements
- **Add forecasting models** for future vegetable prices  
- **Include year-wise comparisons** for long-term trends  
- **Integrate geographic analysis** for region-wise price differences  
- **Add interactive tooltips** with insights per vegetable/month  
- **Enable export of filtered reports** for stakeholders



### Tools Used
- **Power BI Desktop** → **Dashboard creation**  
- **Excel** → **Data storage, cleaning, and preparation**



### Dashboard Preview
![Vegetable Price Insights Dashboard](https://github.com/saurabhgobare/Vegetable_Price_Insights_Dashboard/blob/main/Dashboard/Vegetable%20Price%20Insights%20Dashboard.png)



### How to Use
1. **Download / Clone** this repository  
2. Open **`Vegetable Market Analysis.pbix`** in **Power BI Desktop**  
3. Use the **Item Slicer** to select the vegetable of interest  
4. Hover over charts for **detailed insights**  
5. Check **KPI Cards & Gauge Chart** for quick assessment  
6. Use **Drill-through** for **monthly item price analysis**
