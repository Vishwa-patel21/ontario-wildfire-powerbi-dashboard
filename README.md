# Ontario Wildfire Suppression Analytics Dashboard

A 3-page Power BI dashboard built using official Ontario wildfire datasets to analyze wildfire activity trends, suppression resource rates, and fire severity patterns.

## Project Overview

This project was created to showcase Power BI skills through a structured analytics dashboard based on Ontario wildfire-related public data. The report combines multi-year wildfire activity reporting with 2021 listed suppression resource rates to present a decision-support style dashboard with clear visuals, KPI design, trend analysis, and interactive filtering.

## Dashboard Pages

### 1. Ontario Wildfire Overview
This page provides a high-level summary of wildfire activity in Ontario.

**Includes:**
- Total Fires
- Total Hectares Burned
- Average Hectares per Fire
- Estimated Cost Proxy
- Ontario Wildfire Activity Trend
- Current Year Fires vs Average gauge
- Yearly Summary matrix
- Top Years by Burned Area chart

### 2. 2021 Suppression Resource Rates
This page focuses on the 2021 listed suppression resource rates.

**Includes:**
- Total Listed Resource Rate
- Resource Count
- Resource Rate Share by Category
- Top 10 Resources by Listed Rate
- Rate Breakdown Explorer (Decomposition Tree)

### 3. Fire Severity Insights
This page highlights wildfire severity and impact patterns over time.

**Includes:**
- Current Year Fires
- Current Year Burned Area
- YoY Fire Change %
- YoY Burned Area Change %
- Fire Count vs Burned Area by Year
- Average Hectares per Fire Trend
- Year-over-Year Burned Area Change

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- GitHub

## Data Sources

The dashboard uses official Ontario wildfire-related public datasets:

- Annual forest fire reporting data
- Wildland fire suppression rates (2021)
- Fire disturbance spatial files (downloaded for future geospatial enhancement)

## Key Highlights

- Built a clean 3-page dashboard layout with a consistent navigation and filter panel
- Used multiple visual types including combo chart, gauge, matrix, donut chart, bar chart, decomposition tree, scatter chart, line chart, and waterfall chart
- Applied DAX measures for severity and year-over-year analysis
- Created a structured dashboard design suitable for portfolio and project showcase purposes

## Limitations

- Suppression resource rate data currently used is limited to 2021
- Estimated Cost Proxy is a showcase metric and does not represent audited incident-level suppression spending
- Spatial ZIP files were downloaded but not fully operationalized into map visuals in the current version
- Some advanced wildfire operations metrics would require internal government datasets

## Future Improvements

- Add multiple yearly suppression rate files for stronger cost trend analysis
- Convert spatial wildfire files for map-based reporting
- Move the project into Microsoft Fabric with Bronze, Silver, and Gold layers
- Create a semantic model and automated refresh pipeline

## Repository Structure

```text
ontario-wildfire-powerbi-dashboard/
├── README.md
├── Ontario_Wildfire_Dashboard.pbix
├── images/
│   ├── page1_overview.png
│   ├── page2_resource_rates.png
│   └── page3_severity_insights.png
└── data/
    ├── annual_fire_reporting.csv
    └── suppression_rates_2021.csv
