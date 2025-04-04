# 🏦 Retail Sales Dashboard | PySpark + Power BI

A complete end-to-end data analytics project that simulates a real-world retail sales reporting solution using PySpark for ETL processing and Power BI for business intelligence.

---

## 🎓 Project Overview
This dashboard showcases retail sales performance across regions, product categories, and time using:
- **PySpark + Databricks** for data cleaning and transformation
- **Parquet file storage** for efficient processing
- **Power BI** for data visualization and storytelling

---

## 📊 Tech Stack
| Tool            | Purpose                               |
|------------------|----------------------------------------|
| **Databricks**   | PySpark-based data processing        |
| **PySpark**      | ETL operations & aggregations        |
| **Power BI**     | Interactive data visualization       |
| **Parquet**      | Processed data storage format        |
| **DBFS**         | Databricks File System (stores raw/processed data) |
| **JDBC + Access Token** | Used to securely connect Power BI to Databricks data (simulated in this project) |

---

## 🔄 Data Pipeline Workflow

```
CSV File → Databricks PySpark → Cleaned Aggregates → Parquet (DBFS) → Power BI Dashboard
```

**Data Used**: Superstore Sales dataset (Products, Orders, Profit, Sales, Region, Category)

---

## 🛠️ Connecting Power BI to Databricks

### Simulated JDBC Connection via Personal Access Token (PAT)

To showcase a real-world enterprise integration, this project **demonstrates the workflow for securely connecting Power BI to Databricks using JDBC and Access Tokens**, even though Databricks Community Edition does not support live PAT connections.

📌 **Steps Included in Documentation** (for enterprise use):
1. Go to Databricks → **Settings → Developer** → Generate a **Personal Access Token (PAT)**
2. Use Power BI Desktop → **Get Data → Azure → Azure Databricks**
3. Input your **Server Hostname** and **HTTP Path** (from Databricks SQL endpoint or cluster)
4. Authenticate using the **PAT token** to access Databricks tables directly

✅ In a paid or enterprise environment, this method allows **real-time Power BI refresh** directly from Databricks tables (eliminating manual exports).

🧪 In this project:
- We **processed the data using PySpark in Databricks**
- Saved the **aggregated Parquet files to DBFS**
- Then **loaded those files into Power BI** for final visualizations

> 🔒 Note: Databricks Community Edition **does not support live external connections** (like Power BI via JDBC). Hence, this setup was simulated with exported Parquet data.

---

## 📈 Dashboard Features

### 📊 KPIs
- ✅ Total Sales (formatted with currency)
- ✅ Total Profit (highlighted in green)

### 🌍 Visuals
- **Sales by Region**: Clustered column bar chart
- **Monthly Sales Trend**: Line chart (time series)
- **Sales vs Profit by Category**: Dual-measure bar chart

### 📃 Filters / Slicers
- Filter by Region
- Filter by Product Category
- Filter by Month

---

## 🧠 Key Learnings
- Building a real-world PySpark pipeline in Databricks
- Cleaning and aggregating large datasets
- Loading Parquet outputs into Power BI
- Simulating secure enterprise connections with PAT
- Designing professional, recruiter-ready dashboards

---

## 🔍 Preview
# 🏦 Retail Sales Performance Dashboard | PySpark + Power BI

A complete end-to-end data analytics project that simulates a real-world retail sales reporting solution using PySpark for ETL processing and Power BI for business intelligence.

---

## 🎓 Project Overview
This dashboard showcases retail sales performance across regions, product categories, and time using:
- **PySpark + Databricks** for data cleaning and transformation
- **Parquet file storage** for efficient processing
- **Power BI** for data visualization and storytelling

---

## 📊 Tech Stack
| Tool            | Purpose                               |
|------------------|----------------------------------------|
| **Databricks**   | PySpark-based data processing        |
| **PySpark**      | ETL operations & aggregations        |
| **Power BI**     | Interactive data visualization       |
| **Parquet**      | Processed data storage format        |
| **DBFS**         | Databricks File System (stores raw/processed data) |
| **JDBC + Access Token** | Used to securely connect Power BI to Databricks data (simulated in this project) |

---

## 🔄 Data Pipeline Workflow

```
CSV File → Databricks PySpark → Cleaned Aggregates → Parquet (DBFS) → Power BI Dashboard
```

**Data Used**: Superstore Sales dataset (Products, Orders, Profit, Sales, Region, Category)

---

## 🛠️ Connecting Power BI to Databricks

### Simulated JDBC Connection via Personal Access Token (PAT)

To showcase a real-world enterprise integration, this project **demonstrates the workflow for securely connecting Power BI to Databricks using JDBC and Access Tokens**, even though Databricks Community Edition does not support live PAT connections.

📌 **Steps Included in Documentation** (for enterprise use):
1. Go to Databricks → **Settings → Developer** → Generate a **Personal Access Token (PAT)**
2. Use Power BI Desktop → **Get Data → Azure → Azure Databricks**
3. Input your **Server Hostname** and **HTTP Path** (from Databricks SQL endpoint or cluster)
4. Authenticate using the **PAT token** to access Databricks tables directly

✅ In a paid or enterprise environment, this method allows **real-time Power BI refresh** directly from Databricks tables (eliminating manual exports).

🧪 In this project:
- We **processed the data using PySpark in Databricks**
- Saved the **aggregated Parquet files to DBFS**
- Then **loaded those files into Power BI** for final visualizations

> 🔒 Note: Databricks Community Edition **does not support live external connections** (like Power BI via JDBC). Hence, this setup was simulated with exported Parquet data.

---

## 📈 Dashboard Features

### 📊 KPIs
- ✅ Total Sales (formatted with currency)
- ✅ Total Profit (highlighted in green)

### 🌍 Visuals
- **Sales by Region**: Clustered column bar chart
- **Monthly Sales Trend**: Line chart (time series)
- **Sales vs Profit by Category**: Dual-measure bar chart

### 📃 Filters / Slicers
- Filter by Region
- Filter by Product Category
- Filter by Month

---

## 🧠 Key Learnings
- Building a real-world PySpark pipeline in Databricks
- Cleaning and aggregating large datasets
- Loading Parquet outputs into Power BI
- Simulating secure enterprise connections with PAT
- Designing professional, recruiter-ready dashboards

---

## 🔍 Preview

---

## 📂 Files Included
```
|- notebooks/
|   |- retail_etl_pipeline.ipynb
|- parquet/
|   |- monthly_sales.parquet
|   |- sales_by_region.parquet
|   |- category_summary.parquet
|- dashboard/
|   |- retail_dashboard.pbix
|- README.md
```

---


