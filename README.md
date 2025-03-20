# Vrinda Store Annual Sales Report 2022

## 📌 Table of Contents
1. [Project Overview](#project-overview)
2. [Project Outline](#project-outline)
3. [Key Deliverables](#key-deliverables)
4. [Questions Answered in the Analysis](#questions-answered-in-the-analysis)
5. [Data Preparation & Processing](#data-preparation--processing)
   - [Data Cleaning](#data-cleaning)
   - [Data Processing](#data-processing)
6. [Interactive Dashboard](#interactive-dashboard)
7. [File Links](#file-links)
8. [Insights & Recommendations](#insights--recommendations)
9. [Conclusion](#conclusion)

---

## Project Overview
The objective of this project is to create an Annual Sales Report for Vrinda Store (2022) to help the company gain insights into customer behavior and enhance sales in 2023.

---

## Project Outline
- **Introduction**
- **Data Collection & Cleaning**
- **Data Processing**
- **Data Analysis**
- **Interactive Dashboard Creation**
- **Key Insights & Recommendations**
- **Conclusion**

---

## Key Deliverables
- A detailed **Annual Sales Report** for 2022  
- An **Interactive Dashboard** to visualize key sales metrics  
- **Recommendations** for sales growth in 2023  

---

## Questions Answered in the Analysis:
✔️ **Comparison of Sales vs Orders**  
✔️ **Identification of the Month with Highest Sales**  
✔️ **Analysis of Customer Demographics (Men vs Women)**  
✔️ **Breakdown of Order Statuses (Delivered, Refunded, etc.)**  
✔️ **Top 5 States contributing to sales**  
✔️ **Relationship between Age, Gender, and Sales**  
✔️ **Identification of Best Performing Sales Channel**  
✔️ **Most Profitable Product Categories**  

---

## Data Preparation & Processing

### Data Cleaning
- Standardized the **Gender Column** (m → Male, f → Female)  
- Replaced column inconsistencies (one → 1, two → 2)  
- Checked for **empty cells and errors**  

### Data Processing
- Created an **Age Group** column (Senior, Adult, Teenager)  
- Extracted **Month** from the Date column using:
  ```excel
  =TEXT(G2,"mmmm")
   ```
Built Pivot Tables for key metrics:

Order vs Sales (Line Chart)
Men vs Women Sales (Pie Chart)
Order Status Breakdown (Pie Chart)
Top 5 States by Sales (Bar Chart)
Age & Gender Breakdown (Column Chart)
Sales Channels (Pie Chart)
Added Interactive Slicers for filtering by Month, Channels, and Category.

## Interactive Dashboard

![Vrinda Store Dashboard](Vrinda%20Store%20Data%20Analysis%20dash.png)

###  File Links:
- **Excel Analysis File**: [Download Vrinda Store Data Analysis Dashboard.xlsx](Vrinda%20Store%20Data%20Analysis%20dashboard.xlsx)
- **Raw Data File**: [Download SalesDataset raw data.csv](SalesDataset%20raw%20data.csv)

## Insights & Recommendations
🔹 Peak Sales Month: 📈 Highest sales in March
🔹 Customer Demographics: 👩 Women contribute 64% of sales
🔹 Top Performing Sales Channel: 📦 Amazon (35%)
🔹 Top State for Sales: Maharashtra (2.99M)
🔹 Most Popular Age Group: Adults (34.59%)

## Recommendations:
✅ Invest in targeted marketing for women customers
✅ Expand sales through Amazon and Flipkart
✅ Focus on high-performing states like Maharashtra
✅ Optimize best-selling product categories

## Conclusion
The Vrinda Store 2022 Annual Report provides actionable insights to enhance sales performance in 2023.
The interactive dashboard allows for easy data exploration and better decision-making.
