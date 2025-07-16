# sales-report-dashboard

## 📊 Overview
This project visualizes sales and customer data for a supermarket using Power BI. The dashboard offers insights into customer locations, sales trends, and transactional metrics.

## 🗂️ Datasets
- **CustomerDetails.csv** – Contains customer demographics and location info.
- **InvoiceData.txt** – Contains transactional data including date and sales figures.

## 🧹 Data Cleaning & Transformation (Power Query)
Data was pre-processed in Power Query with the following steps:
- Converted the **Sales** column to a currency data type.
- Combined **Day**, **Month**, and **Year** columns into a single **Date** column for time-based analysis.
- Split a combined **City-Province** column into two separate columns to improve geographic insights.
- Merged the datasets using a common identifier to create a single model for analysis.

## 📈 Key Features in the Dashboard
- Sales over time visualized using line and column charts.
- Customer segmentation by city and province.
- Drill-downs for invoice-level data.
- Dynamic filters for date, location, and customer profiles.

## 📁 Files in This Repo
- `SupermarketDashboard.pbix` – The main Power BI dashboard file.
- `CustomerDetails.csv` – Raw customer data.
- `InvoiceData.txt` – Raw sales/invoice data.

## 🛠 Tools Used
- Power BI
- Power Query
- DAX (basic level for measures)

## 🔗 Video Demo
A screen recording showing the dashboard's features is available on [LinkedIn](https://www.linkedin.com/posts/richmondabake_powerbi-dataanalytics-dashboard-activity-7351223038886981636-9dnG?utm_source=share&utm_medium=member_desktop&rcm=ACoAAClmzuIB2rot2QSdNpYj81gezWSw5ZV61zE).

---

Feel free to fork, star, or use the dataset for your own experiments.

Special appreciation to Leila Gharani for the insights.

