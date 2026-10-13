# CavinKare FMCG — Distributor Sales & Marketing Analytics

## 📌 Project Overview

The **CavinKare FMCG Distributor Sales & Marketing Analytics** project focuses on analyzing distributor sales performance, product trends, outlet performance, and regional business growth using Power BI.

The project transforms raw distributor sales data into actionable business insights through data cleaning, dimensional modeling, advanced DAX calculations, and interactive dashboards. It helps stakeholders monitor sales performance, identify top-performing products and outlets, and make data-driven business decisions.

## 🎯 Business Objectives

- Analyze overall sales performance across regions and distribution zones.
- Identify top-performing products, brands, and outlets.
- Track sales trends and year-over-year growth.
- Evaluate distributor and outlet performance.
- Provide role-specific dashboards for business stakeholders.
- Implement Row-Level Security (RLS) to control access to zone-specific data.

## 🛠️ Tools & Technologies

- **Power BI** — Interactive dashboards and business reporting.
- **Power Query** — Data cleaning, transformation, and ETL.
- **DAX** — Business calculations, ranking, and time intelligence.
- **Data Modeling** — Star schema and dimension tables.
- **Row-Level Security (RLS)** — Zone-based data access control.

## 📂 Dataset Overview

The project uses distributor sales data covering:

- **6,150+** raw sales records before cleaning.
- **6,000** curated sales records after data cleaning.
- **400** outlets.
- **11** brands.

The dataset supports analysis of sales transactions, products, outlets, dates, and regional performance.

## 🔄 Data Cleaning & ETL

Power Query was used to build the data transformation pipeline.

Key data preparation steps included:

1. Standardized inconsistent date formats.
2. Cleaned currency symbols and converted sales values into appropriate numeric data types.
3. Standardized inconsistent region labels.
4. Checked data quality and removed or resolved identified data issues.
5. Prepared a curated 6,000-row fact table for analysis.
6. Validated transformed data before loading it into the Power BI data model.

## 🏗️ Data Modeling

Implemented a **star schema** to organize transactional data and support efficient analytical reporting.

### Model Structure

- **Fact_Sales** — Stores distributor sales transactions and measures.
- **Dim_Product** — Contains product and brand attributes.
- **Dim_Outlet** — Contains outlet and regional attributes.
- **Dim_Date** — Supports date-based and time-intelligence analysis.

The dimension tables connect to the central Fact_Sales table through appropriate relationships, enabling consistent filtering and cross-dashboard analysis.

## 📊 DAX Measures & Analytics

Developed **15+ DAX measures** to calculate key business metrics and support interactive analysis.

Functions used include:

- `CALCULATE()` — Evaluates measures under specific filter conditions.
- `RANKX()` — Ranks products, brands, or outlets by performance.
- `SAMEPERIODLASTYEAR()` — Supports year-over-year comparisons.
- Time-intelligence calculations — Analyze sales trends and growth over time.
- Filter-context calculations — Enable dynamic analysis by region, product, outlet, and date.

Example measures include total sales, sales by brand, outlet ranking, previous-year sales, and year-over-year sales growth, depending on the available dataset fields.

## 📈 Dashboard Modules

The project includes three role-specific dashboards designed to support different business users.

### 1. Executive Sales Overview
- Monitor overall sales performance.
- Analyze sales trends over time.
- Compare regional and brand performance.
- Identify key growth areas and underperforming segments.

### 2. Distributor & Outlet Performance
- Compare performance across 400 outlets.
- Rank outlets based on sales.
- Identify high-performing and low-performing distribution zones.
- Evaluate regional sales contribution.

### 3. Product & Marketing Analytics
- Analyze performance across 11 brands.
- Compare product and brand sales.
- Identify leading and underperforming products.
- Support product-level and regional marketing decisions.



## 💡 Business Value

This project demonstrates how raw FMCG distributor sales data can be converted into structured business intelligence.

Key benefits include:

- Improved visibility into regional sales performance.
- Faster identification of top-performing brands and outlets.
- Better tracking of sales growth and historical trends.
- More consistent reporting through centralized data modeling.
- Controlled access to zone-specific business information.
- Data-driven support for sales planning and marketing decisions.

## 🚀 Skills Demonstrated

- Data Cleaning & Transformation
- ETL Pipeline Development
- Star Schema Data Modeling
- DAX Measure Development
- Time Intelligence
- Sales Performance Analysis
- Product & Outlet Ranking
- Interactive Dashboard Development
  
- Business Intelligence & Reporting

## 👩‍💻 Author

**Suganya G.**

Aspiring Data Analyst | Power BI | SQL | Excel | Python

