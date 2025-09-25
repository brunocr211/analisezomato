# Zomato-Analysis (interactive dashboard creation using Excel/Power BI/Tableau) and SQL

## Project Objective
The objective of this project is to analyze Zomato restaurant data to uncover insights about restaurant trends, customer preferences, and key factors influencing ratings and pricing. The goal is to help businesses, restaurant owners, and stakeholders make data-driven decisions for improving service quality, menu pricing, and customer satisfaction.

## Dataset used
<a href="https://github.com/Rakshithabadiger/Zomato-Analysis/blob/main/Zomata%20-%20Copy.xlsx"> Data set </a>

## Process
- Data Understanding
  Explored the dataset to identify key features such as restaurant name, location, cuisine types, ratings, votes, cost, and online delivery options.
  Checked for missing values, duplicates, and outliers.
- Data Cleaning & Preparation
  Removed duplicate records and irrelevant columns.
  Handled missing values using appropriate imputation techniques.
  Standardized column names and formatted categorical data (e.g., cuisines, city names).
  Converted numerical columns to proper data types for analysis.
- Exploratory Data Analysis (EDA)
  Analyzed restaurant distribution across cities and cuisines.
  Examined relationships between ratings, votes, and cost.
  Compared restaurants offering online delivery vs. those without.
  Visualized trends using bar charts, heatmaps, and interactive dashboards.
- Visualization & Dashboarding
  Built interactive dashboards in Power BI/Tableau to present insights clearly.
  Created key KPIs like average ratings, cost distribution, and popular cuisines.

## Questions (KPIs and Charts)
1. Build a Data Model using the Sheets in the Excel File
2. Build a Calendar Table using the Columns Datekey_Opening ( Which has Dates from Minimum Dates and Maximum Dates)
  Add all the below Columns in the Calendar Table using the Formulas.
   A.Year
   B.Monthno
   C.Monthfullname
   D.Quarter(Q1,Q2,Q3,Q4)
   E. YearMonth ( YYYY-MMM)
   F. Weekdayno
   G.Weekdayname
   H.FinancialMOnth ( April = FM1, May= FM2  …. March = FM12)
   I. Financial Quarter ( Quarters based on Financial Month FQ-1 . FQ-2..)
3. Convert the Average cost for 2 column into USD dollars (currently the Average cost for 2 in local currencies
4.Find the Numbers of Resturants based on City and Country.
5.Numbers of Resturants opening based on Year , Quarter , Month
6. Count of Resturants based on Average Ratings
7. Create buckets based on Average Price of reasonable size and find out how many resturants falls in each buckets
8.Percentage of Resturants based on "Has_Table_booking"
9.Percentage of Resturants based on "Has_Online_delivery"
10. Develop Charts based on Cusines, City, Ratings ( Candidate have to think about new KPI to analyse)
11. Build a Dashboard for the KPI's Above.
-  you can experiment on the other KPI as well.

## Dashboards
- EXCEL<img width="1581" height="706" alt="EXCEL Dashboard snapshot" src="https://github.com/user-attachments/assets/01ad263c-d2b8-4a70-8fa0-5a1eee2acc39" />
- POWER BI<img width="1706" height="779" alt="Power BI Dashboard snapshot" src="https://github.com/user-attachments/assets/bddbf4af-4b5f-449f-8501-34c022794dd3" />
- TABLEAU<img width="1709" height="775" alt="Tableau Dashboard snapshot" src="https://github.com/user-attachments/assets/11423a1c-be87-4569-b2fa-275d279287c4" />

## Project Insights
- Top Performing Cities: Major metro cities like Bangalore, Delhi, and Mumbai dominate the restaurant market.
- Popular Cuisines: North Indian and Chinese cuisines are the most frequently listed and widely preferred.
- Rating Trends: Restaurants with online delivery and higher votes tend to have better ratings.
- Cost Analysis: High-rated restaurants generally maintain moderate cost ranges, suggesting value-for-money influences customer satisfaction.

## Data Cleaning
- Dropped unnecessary columns like url and address which did not add analytical value.
- Removed inconsistent location/cuisine entries and standardized category names.
- Treated missing ratings and cost values to ensure accurate visualization.
- Converted cost values to a uniform currency format for analysis.

## SQL Queries


## Final Conclusion
The analysis of Zomato’s restaurant data provides valuable insights into customer preferences, cost dynamics, and city-wise trends. Restaurants can leverage these findings to optimize their menus, pricing strategies, and service offerings. This project demonstrates how data cleaning, visualization, and exploratory analysis can transform raw data into actionable business intelligence.
