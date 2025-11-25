# 📊 Data Jobs Dashboard 2.0
## 📘 Project Description

The **Data Jobs Dashboard 2.0** is a single-page Power BI analytics report designed to explore the global data-related job market.
It provides an interactive visual breakdown of:

- Most in-demand data skills

- Job availability and skill requirements

- Salary benchmarks across different roles

- Country- and job-specific segmentation

This dashboard is aimed at data professionals, analysts, and HR teams who want to quickly understand trends in the data job ecosystem.

## 🚀 Features & Capabilities
### 🔹 Key KPI Metrics

- Job Count: Total number of jobs found (479K)

- Skills Per Job: Average number of skills required (4.8)

- Median Yearly Salary: ~$113K

- Median Hourly Salary: ~$48

### 🔹 Interactive Visuals

**Skill Popularity Chart**

- Displays most in-demand skills such as Python, SQL, AWS, Azure, Tableau, etc.

- Toggle between **Job Percent** and **Job Count** view.

**Job Salaries Chart**

- Compares yearly median salaries for roles such as Senior Data Scientist, ML Engineer, Data Engineer, Software Engineer, etc.

- Toggle between **Median Yearly Salary** and **Median Hourly Salary**.

### 🔹 Filters & Slicers

- **Job Title selector**

- **Country selector**

- **Clear All Slicers** button

All visuals support cross-filtering for intuitive exploration.

## 📂 Dataset Details

The underlying dataset includes job listings enriched with fields such as:

- Job Title

- Country

- Required Skills

- Yearly and Hourly Salaries

- Skill Frequency / Job Count

### Data Cleaning (Power Query)

- Removed duplicates and unnecessary fields

- Standardized job titles & country names

- Extracted and normalized skill lists

- Converted salary fields to numeric types

- Ensured consistent formatting

### Data Model

- Star-schema inspired layout

- Skill/Job fields transformed into relational tables

- Measures created using DAX for KPIs and dynamic toggles

### DAX Measures Used

Examples include:

- **Total Job Count**

- **Average Skills Per Job**

- **Median Yearly Salary**

- **Median Hourly Salary**

- Skill frequency measures

- Switch() logic for role-based button toggles

## 🧭 How It Works
### Single Dashboard Page

The entire experience is designed around one powerful, consolidated page:

- KPIs on top for fast insight

- Filters for instant segmentation

- Skills and salaries displayed side-by-side

- Toggle buttons to switch the view mode of each visual

- Smooth, interactive scrolling inside charts

- All visuals connected for cross-highlighting

- There are no drill-through pages in this version.

## 🛠 Technical Stack

**Power BI Desktop**

**Power Query** for ETL

**DAX** for calculations

Optional: Power BI Service for publishing

## 📥 Setup Instructions

**1.** Download the file:
**2_Dashboard_Project_2.0.pbix**

**2.** Open with **Power BI Desktop** (latest version).

**3.** Refresh the data via:
**Home → Refresh**

**4.** Use slicers (Job Title / Country) to explore the dataset.

**5.** Use toggle buttons at the bottom of each chart to switch metrics.
## 🖼 Screenshots
![Salary Dashboard Gif](1_resources/images/Project2_Dashboard_Overview.gif)


![Salary Dashboard Preview](1_resources/images/Project2_Dashboard_Page1.png)
## 📈 Insights Summary

This dashboard provides insights such as:

- **Python and SQL are the most in-demand data skills**

- Cloud skills (AWS, Azure) are becoming essential

- Senior roles have significantly higher compensation

- Skill requirements average nearly **5 skills per job**

- Salary varies heavily by job role and region

These insights help job seekers, analysts, and companies understand the current landscape of data jobs and make informed decisions.
## 📄 License

This project is licensed under the MIT License, allowing reuse and modification.