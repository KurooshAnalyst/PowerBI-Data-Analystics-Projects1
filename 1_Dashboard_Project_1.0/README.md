# 📊 Power BI Dashboard Project
## 📘 Project Description

This Power BI project presents a comprehensive, interactive dashboard designed to analyze key business performance indicators.
The report aims to help decision-makers quickly understand trends, identify operational bottlenecks, and monitor essential metrics.
The dataset used in this project includes structured business data containing categories such as transactions, dates, customer information, and performance metrics.

The dashboard includes two pages:

**1. Main Dashboard – A high-level overview of all major KPIs and visuals.**

**2.Drill-Through Page – A detailed view allowing users to analyze specific items selected from the main page.**

## 🚀 Features & Capabilities

- Interactive data visualizations using charts, cards, and tables

- KPI tracking across multiple categories (e.g., revenue, performance trends, comparisons)

- Drill-through insights for deeper analysis

- Slicers and filters for dynamic exploration

- Data transformations using Power Query

- Logical calculations implemented with DAX measures

- Automated data modeling and relationship management

- Clean and intuitive layout focused on actionable insights

## 📂 Dataset Details

The dataset was imported and transformed using Power Query. Key steps include:

- **Data Cleaning:**

    - Removal of duplicates

    - Standardization of column formats

    - Type conversion of numeric, date, and text fields

- **Data Modeling:**

    - Relationship creation between fact and dimension tables

    - Normalization of repeated fields

- **DAX Measures:**

    - Custom KPIs such as totals, averages, YOY changes, and conditional metrics

    - Calculated columns for categorization and segmentation

Data sources may include structured CSV, Excel, or database exports (depending on the version of the project uploaded).

## 🧭 How It Works
### Main Dashboard

- Provides a complete overview of the dataset through KPIs, charts, and summary visuals

- Slicers allow filtering by date, category, customer segment, and other attributes

- Clicking specific elements triggers drill-through actions

## Drill-Through Page

- Displays detailed information about a selected data point (e.g., category, product, region)

- Designed for deeper analysis and supporting root-cause investigation

## 🛠 Technical Stack

- **Power BI Desktop**

- **Power Query for ETL (Extract, Transform, Load)**

- **DAX (Data Analysis Expressions)** for custom calculations

- Optional tools (if used):

    - DAX Studio

    - Power BI Service (for publishing)

## 📥 Setup Instructions

**1.** Download the project file:
2_dashboard_project.pbix

**2.** Open the file using **Power BI Desktop** (latest version recommended)

**3.** If a data source path is required, update it using:
**Home → Transform Data → Data Source Settings**
**4.** Refresh the report:
**Home → Refresh**

**5.** Interact with slicers, visuals, and drill-through navigation
## 🖼 Screenshots
![Data Start Schema](Data_star_schema-1.png)

![Page 1 Preview](Project1_Dashboard_Overview-1.gif)

![Page 1 Photo](Project1_Dashboard_Page1.gif)

![Drill Through](Project1_Dashboard_Page2.gif)

## 📈 Insights Summary

- Key insights discovered from the analysis may include:

- Identification of high-performing categories and underperforming segments

- Trends and seasonality patterns within the business data

- Breakdown of performance by time, category, customer type, or region

- Drill-through results that highlight root causes behind anomalies

- Opportunities for optimization based on visualized KPIs
## 📄 License

This project is released under the MIT License.
Feel free to use, modify, and distribute the content.