# 🧠 Power BI Sales and Customer Performance Dashboard

## 📌 Problem Statement

The goal of this project was to build a comprehensive sales and customer analytics dashboard using Power BI, with all data transformation handled entirely within Power Query. The project aimed to enable better decision-making by analyzing key sales KPIs, customer segments, and performance trends across time, geography, and product lines.

---

## 🛠️ Power Query Data Transformation

- Cleaned and standardized raw datasets
- Handled missing or inconsistent data values
- Created all necessary join keys using Power Query only
- Merged datasets (Sales, Returns, Targets, Products, Customers, Salespersons)
- Added calculated columns for KPIs such as:
  - Total Sales (Sales - Returns)
  - % Target Achieved
  - % Margin (Profit / Sales Amount)
  - Discount Amount

---

## 📊 KPI Metrics & Business Insights

### 🔹 Sales Performance Analysis (4 Sub-Views)

1. **Overall Sales Trends**
   - Sales trend over the past 4 years
   - Year-over-Year comparison
   - Sales breakdown by Region, Segment, and Category
   - Key KPIs tracked with dynamic visuals

2. **Target / Benchmark Analysis**
   - Highlighted regions and states that achieved/not achieved sales targets
   - % Target Achievement shown by geography

3. **What-If Analysis**
   - User-defined input for discount % by segment
   - Predictive calculation of Profit % based on selected discounts

4. **Pareto Analysis**
   - Interactive analysis to identify what % of sales is contributed by top X% of customers
   - User control to define Pareto threshold

---

### 🔹 Customer Analysis

- **RFM Segmentation**
  - Recency based on last 180 days of transactions
  - Frequency of purchases
  - Monetary value of total purchases
  - Customers segmented into Low, Medium, and High value groups
  - Segment-wise sales contribution visualized

- **New Customer Analysis (2021)**
  - Number of new customers acquired
  - Total sales and quantity purchased
  - Discounts offered to new customers

- **Targeted Marketing Scoring**
  - Scoring logic based on RFM
  - Identified high-potential customers for targeted campaigns and retention strategies

---

### 🔹 Salesperson Performance

- Top 5 performing salespersons by:
  - Segment
  - State
  - City
- Visuals show:
  - Total Sales made
  - Average Discount % provided by each salesperson

---

## 📈 Tools Used

- Power BI Desktop
- Power Query for all transformations
- DAX for KPIs and custom calculations
- Excel (Sample raw data)

---

## 💡 Outcome

- Created a scalable and interactive BI solution
- All data modeling and transformation done without external scripts or SQL
- Delivered business-ready dashboards with self-serve capabilities for deeper insights

---

## 📁 Project Structure

- `PowerBI-Dashboard.pbix` – Main Power BI dashboard file
- `Dataset/` – Contains sample CSVs used for this project
- `README.md` – Project overview and documentation

---

## 🧭 How to Use

1. Clone or download the repository
2. Open the `.pbix` file in Power BI Desktop
3. Review the dashboards and interact with filters, slicers, and What-If inputs

---
