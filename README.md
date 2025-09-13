# 📊 Blinkit Sales Analysis Project

##  Overview
This project presents an **end-to-end sales analysis** of Blinkit data using **SQL, Python, and Power BI**.  
The objective is to explore sales performance, identify trends across products and outlets, and provide actionable insights for decision-making.  

The workflow covers:  
1. **Data Cleaning** (SQL & Python)  
2. **Exploratory Data Analysis (EDA)** using Python  
3. **Business KPI calculation** using SQL  
4. **Interactive Dashboard** in Power BI  

By combining these three technologies, this project demonstrates the complete **data analyst skillset** — from raw data to insights visualization.

## 🛠️ Tech Stack
- **SQL**
  - Data Cleaning & Transformation
  - KPI and Aggregation Queries
  - Window Functions for growth analysis

- **Python**
  - Libraries: Pandas, NumPy, Matplotlib, Seaborn
  - Exploratory Data Analysis (EDA)
  - Visualizations of trends and distributions

- **Power BI**
  - Interactive Dashboards
  - KPI cards, charts, slicers for filtering
  - Professional report design

## 🔍 Analysis Performed

### 1. Data Cleaning
- Standardized categorical values (e.g., converting 'LF' and 'low fat' → 'Low Fat').  
- Removed duplicates and ensured correct data types.  
- Validated sales and rating fields.  

### 2. SQL Analysis
- **Total & Average Sales**
- **Sales distribution by Item Fat Content, Item Type, Outlet Type, Size, and Location**
- **Top 10 and Bottom 10 product categories**
- **Year-over-Year Sales Growth using window functions (LAG)**  
- **Percentage share of sales by Outlet Size**  

### 3. Python EDA
- Univariate & Bivariate Analysis (Sales distribution, Rating distribution, Outlet performance)  
- Correlation heatmaps to identify relationships between variables  
- Boxplots, barplots, and histograms for trend identification  
- Time-based analysis of establishment year sales  

### 4. Power BI Dashboard
- **KPIs:** Total Sales, Average Sales, Number of Items, Average Rating  
- **Charts:**  
  - Donut chart for sales % by Outlet Size  
  - Bar chart for sales by Item Type  
  - Line chart for Year-over-Year sales growth  
  - Slicers for interactive filtering (Outlet Location, Item Type, Year)  


## 📊 Key Insights
- **Regular items** generated higher sales compared to Low Fat products.  
- **Medium-sized outlets** contributed the maximum percentage of overall sales.  
- Certain product categories consistently dominated sales, while others underperformed.  
- Outlets established in recent years showed **positive sales growth**, while older outlets had stable but lower sales.  
- **Tier-3 outlet locations** surprisingly contributed significantly, showing untapped market potential.  


## 📈 Dashboard Preview
The interactive Power BI dashboard highlights key business KPIs and trends.

![Dashboard Screenshot](Screenshot.png)

## 📂 Project Structure

Blinkit-Sales-Analysis/
│── blinkitproject.ipynb      # Python notebook (EDA & visualizations)
│── BLINKIT PROJECT(sql).docx # SQL queries and results
│── Screenshot.png             # Power BI dashboard screenshot
│── README.md                  # Project documentation

## 🚀 Skills Demonstrated
- **SQL:** Data Cleaning, Aggregations, Joins, Window Functions  
- **Python:** Pandas, NumPy, Visualization with Matplotlib/Seaborn  
- **Power BI:** Dashboarding, KPI cards, Filters & Slicers, Report Design  
- **Analytical Thinking:** Translating raw data into actionable insights  
- **Data Storytelling:** Presenting insights in a structured and visual format  

## 🔗 Future Improvements
- Expand Python analysis with **Machine Learning** (Sales prediction models).  
- Automate SQL scripts into an **ETL pipeline** for real-time updates.  
- Deploy dashboard to **Power BI Service** for online access.  
- Build a Flask/Streamlit app to integrate SQL + Python analysis in one place.  

## 📬 Contact
👩‍💻 **Author:** Apoorva V Dodwad  
📧 **Email:** apoorvavilasdodwad22@gmail.com  
🔗 **GitHub:** [apoorva-2004](https://github.com/apoorva-2004)

