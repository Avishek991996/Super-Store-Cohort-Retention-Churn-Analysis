# Monthly Cohort, Retention, Churn analysis of Super Store

## Source of Dataset
UC Irvine Machine Learning Repository, link : https://archive.ics.uci.edu/dataset/502/online+retail+ii

## Problem Statement
Understanding customer retention and behavior over time is critical for business growth and sustainability. This project aims to analyze the retention rates of customers acquired between December 2009 and April 2010, identifying trends and patterns in customer engagement across different cohorts. The analysis seeks to answer the following questions:

1. How do customer retention rates change month by month for each cohort?
2. What are the critical periods where customer retention declines significantly?
3. What actionable insights can be drawn to improve customer retention strategies in the future?

## Objective
Comprehensive analysis of Superstore customer data focusing on cohort segmentation, retention trends, and churn prediction. The project utilizes advanced data analytics techniques to derive actionable insights for enhancing customer loyalty

## Analysis
The analysis performed in this project includes:

- **Data Transformation in Power Query Editor**: This includes Trim extra spaces, merged columns, remove duplicates, remove null values, addition of new columns, merge queries, creating new table  - **Data Modelling**: Creating relationships between tables, check cardinality, check cross filter direction as per usecase
- **DAX Queries**: Creating new measure(Active customers, Churn rate, Churned customers, Cohort performance, Lost customers, New customers, Resurrected customers, Retained customers, Retention rate, Validation), creating new columns, use functions like sum,count,average,if etc, use of date,year function, logical function.
- **Dashboard Building**: Usage of Stacked stacked column, Table, Matrix, slicer, card, KPI.

### Insights from the Analysis

- **New,Retained and Ressurected customers' count by month, year**:
  - In December 2009, new customers 955
  - After first month new customers 383(53.19%),retained customer 337(46.81%)
  - Number of new customers gradually dropped by 11.48% in November 2011
  - Number of retained customer in december 2011, 371(60.33%) and number of resurrected customers 216(35.12%)

## Tool Used
- Microsoft Power BI: Data transformation (Power Query Editor), data modelling, DAX.

## Repository Structure
- **Data**: Contains the dataset files used for the analysis.
- **README.md**: This file, providing an overview of the project and instructions for reproducing the analysis.
- **Cohort Report**: This file, providing an overview of the project dashboard for reproducing the analysis.

## Contributions
Contributions to improve the analysis or add new features are welcome. If you find any issues or have suggestions for enhancements, feel free to open an issue or submit a pull request.
