# E-Commerce:- Swiggy Data Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Prepration](#Data-Prepration)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Analysis](#Data-Analysis)
- [Findings](#Findings)


### Project Overview

<img width="666" height="375" alt="Delivery boy" src="https://github.com/user-attachments/assets/8d83c773-62bd-4630-80c9-c61c74654bfa" />

This project focuses on analyzing Swiggy's sales, user behavior, city-wise performance, and restaurant trends using Power BI. The goal was to extract meaningful business insights to help stakeholders make data-driven decisions. The interactive dashboards allow filtering by city, cuisine, gender, age, and more to provide a 360° view of performance.



### Data Sources

Mock Swiggy transactional dataset (CSV files)

- Datasets included:

- Order details

- User demographics

- City-wise performance metrics

- Restaurant details and cuisine pricing

- Year-wise and category-wise sales
  

### Tools 
- Power BI Desktop: For data modeling, DAX measures, and dashboard creation

- Microsoft Excel: For initial data cleaning and formatting

- DAX (Data Analysis Expressions): For custom calculations and KPIs

### Data Prepration

- Cleaned raw data using Power Query:

 - Removed nulls, handled blanks

 - Standardized column names

 - Created relationships between tables (user, city, orders, ratings)

- Created custom calculated columns for:

 - Average order value by category

 - Total sales by city/year/restaurant

 - Rating metrics and cuisine performance

- Built a proper star schema for optimal performance


### Exploratory Data Analysis 

Conducted EDA to discover patterns and trends:

- Distribution of orders by Veg, Non-Veg, Others
- City-level sales trends and top 10 performing cities
- User demographics by gender, age, and occupation
- Restaurant performance across cuisines and regions
- Year-on-Year growth in quantity and sales


### Data Analysis

1. Overview Page

  - KPIs: Total Orders, Users, Top 10% Customers, Ratings

  - Category Analysis: Veg, Non-Veg, Others with average price and count

  - Sales trends over the years

2. User Performance Page

  - Gender-wise and Age-wise customer insights

  - Breakdown of occupation and marital status

  - Top contributing age groups and segments

3. City Overview Page

  - Total cities covered

  - Current vs Previous Year sales comparison

  - City-wise performance: Sales, User count, Rating count

  - Map visualization for geographical insights

4. Restaurant Analysis Page

  - Restaurant Count by City

  - Cuisine pricing trends

  - Top-rated restaurants and customer feedback

  - Most popular cuisine combinations across restaurants



###  Findings
- Tirupati generated the highest sales value among all cities (₹43M+)

- Veg orders dominate the market (65% share), but Non-Veg has higher average price

- Bikaner recorded the highest number of users and ratings — indicating strong customer engagement

- Major user base falls between ages 22-24, with students being a large consumer group

- Indian + Chinese cuisine combinations are most offered across restaurants

- Year 2018 marked the peak growth in quantity ordered, followed by a decline in 2020 (possibly due to pandemic impact)


### 🚀 What I Learned

- Building complex data relationships in Power BI

- Creating dynamic visuals and drill-through reports

- Applying business logic using DAX

- Storytelling with data: how to design visually clean, insight-rich dashboards

- Data-driven decision making using real-world metrics



### 🔗 Screenshots



<img width="1329" height="792" alt="SwiggyOverview" src="https://github.com/user-attachments/assets/84bef9f4-dcb8-4aa9-8f1b-20cf9542578d" />




<img width="1320" height="793" alt="SwiggyUserPerformance" src="https://github.com/user-attachments/assets/1ae9790e-cabf-4130-9696-8206da02ccf2" />



<img width="1338" height="792" alt="SwiggyCityOverview" src="https://github.com/user-attachments/assets/ade7c853-b307-4268-b45d-4c9b5a5c1f3f" />



<img width="1334" height="804" alt="SwiggyRestaurantAnalysis" src="https://github.com/user-attachments/assets/27547926-867c-4ef6-9394-dbfd3672bb4c" />








