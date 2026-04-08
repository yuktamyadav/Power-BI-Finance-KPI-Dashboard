# 📊 Finance KPI Dashboard

## 📌 Description

An end-to-end financial analytics dashboard built on Power BI to analyse a fintech firm's sales performance. The dashboard focuses on sales targets, and individual salesperson and team performance through structured KPIs and interactive visualizations. It enables data-driven decision-making by identifying high-performing salespersons and teams, profitable time periods, sales trends using ML, and targets achieved — helping the business optimize sales strategy, team allocation, price revisions, target realignment, and market expansion.

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

- **Power BI Desktop** – Main data visualization platform used for report creation
- **Power Query** – ETL, data transformation, and cleaning layer for reshaping and preparing the data
- **DAX (Data Analysis Expressions)** – Used for calculated measures, dynamic visuals, and conditional logic
- **Data Modelling** – Relationships established among 2 fact tables (Actual, Targets) and 2 dimensional tables (dimPeople, Calendar) to enable cross-filtering and aggregation
- **Data Visualizations** – To visualize sales KPIs and other metrics
- **File Formats** – `.pbix` for development and `.png` for dashboard previews

## 🗄️ Dataset

A mock dataset of a fintech firm provided in Excel format. The dataset consists of 2 fact tables and 2 dimensional tables structured as follows:

**Actual Table**
- Columns: Sales Person, Month, Sales
- DAX Measures: Actual Total Sales, Variance, Variance %, YTD Actual Sales, YTD Variance, YTD Variance %

**Targets Table**
- Columns: Sales Person, Month, Sales Target
- DAX Measures: Target Total Sales, Target Status, YTD Target Sales

**dimPeople Table**
- Columns: Picture, Sales Person, Team

**Calendar Table**
- Columns: Date, Year, Month, Month Name

## 💡 Features / Highlights

### 📈 Key Finance KPIs Tracked

- **Actual Total Sales** – Overall revenue generated
- **YTD Actual Sales** – Overall revenue generated for a year
- **Target Total Sales** – Overall target revenue
- **YTD Target Sales** – Target revenue required for a year
- **Variance** – Difference between Actual Total Sales and Target Total Sales
- **YTD Variance** – Variance for a year
- **Variance %** – Variance with respect to Target Total Sales, expressed as a percentage
- **YTD Variance %** – Variance % for a year
- **Months Target Reached** – Months when Variance exceeded 0

### 📉 Analytical Tools & Visualizations

- **Table Chart** – Displays metrics such as Sales Person, Picture, Actual Total Sales, Target Total Sales, Variance %, and an integrated Sparkline for Actual Total Sales per salesperson
- **Clustered Column Chart** – Compares Actual and Target Total Sales across different months
- **Stacked Column Chart** – Compares Target Status across different months
- **Multi Layout Card** – Displays numerical values for several Finance KPIs
- **Slicer Filter** – Filters data by different Sales Person teams
- **Narrative** – Provides textual insights and outcomes from the data using ML

## 🖼️ Project Screenshot

!([Finance KPI Dashboard.png](https://github.com/yuktamyadav/Power-BI-Finance-KPI-Dashboard/blob/main/Finance%20KPI%20Dashboard.png)) 
