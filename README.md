# 🚀 Retail Sales Data Pipeline using Microsoft Fabric

## 📌 Project Overview
This project demonstrates an end-to-end data engineering and analytics workflow using Microsoft Fabric.

The goal was to transform raw retail transactional data into predictive business insights through data cleaning, feature engineering, machine learning, and visualization.

---

## 🛠️ Technologies Used
- Microsoft Fabric
- Lakehouse Architecture
- SQL
- PySpark
- Python (Pandas, Scikit-learn)
- Power BI

---

## 🔄 Project Workflow

### 1️⃣ Data Ingestion
- Uploaded raw sales dataset into Microsoft Fabric Lakehouse
- Converted raw files into structured tables

### 2️⃣ Data Exploration
- Queried data using SQL endpoint
- Identified duplicate records
- Validated data quality

### 3️⃣ Data Transformation
Using Fabric Notebooks and PySpark:
- Removed duplicate records
- Standardized date formats
- Cleaned and prepared data for analytics

### 4️⃣ Feature Engineering
Created a new business metric:

```python
TotalSales = Quantity * UnitPrice + TaxAmount
```

This transformed raw transactional data into meaningful business insights.

### 5️⃣ Machine Learning
Using Python and Scikit-learn:
- Aggregated historical sales data
- Built a Linear Regression model
- Predicted future sales trends

---

## 📈 Business Value
This solution helps businesses:
- Forecast future sales
- Identify revenue trends
- Improve inventory planning
- Support data-driven decision-making

---

## 📷 Project Screenshots

Find them on the above information as they are each name with exactly what is being displayed.

## 🔮 Future Improvements
- Advanced forecasting models
- Real-time streaming analytics
- Interactive Power BI dashboards

---

## 👤 Author
Xolani Ngidi
