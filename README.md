# SQL-Project
SQL Student Performance Analysis Project

Project Overview
This project demonstrates SQL data analysis using a student performance dataset.  
The aim is to explore academic, behavioral, and environmental factors that influence exam performance and to answer practical, business-style questions using SQL queries.
The project focuses on data retrieval, filtering, aggregation, grouping, conditional logic, and basic data quality checks.

Tools that I used are
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- GitHub

Dataset Description
The dataset contains information related to student performance and background factors.

Database Table
Table Name is StudentPerformanceFactors

The table stores student academic results and supporting factors, enabling analysis through SQL queries.


SQL Concepts Demonstrated
This project demonstrates the following SQL concepts:
- Data retrieval using SELECT
- Filtering data using WHERE
- Sorting results using ORDER BY
- Aggregate functions: SUM, COUNT, AVG, MIN, MAX
- Grouping data using GROUP BY
- Handling NULL values
- Removing duplicate values using DISTINCT
- Subqueries
- Conditional logic using CASE
- Basic joins
- Data quality checks

Key Analysis Performed
 Data Exploration
- Retrieved all records from the table
- Selected specific columns for focused analysis
- Sorted exam scores in descending order

Aggregation & Statistics
- Total exam scores using SUM
- Minimum, average, and maximum of previous scores
- Counted students with recorded previous scores
- Calculated minimum, average, and maximum exam scores per gender

Gender-Based Analysis
- Total number of students per gender
- Students per gender with previous scores above 60
- Students per gender with exam scores below 60
- Handling missing gender values using ISNULL

Performance Evaluation
- Categorised exam performance using CASE
  - Almost pass
  - Pass
  - Distinction
- Identified students with low motivation or poor attendance
- Analysed relationships between previous scores and exam results

Data Quality Checks
- Identified records with missing parental education level
- Removed duplicate exam score values using DISTINCT
Joins
- Demonstrated joins to explore relationships between study habits, sleep hours, motivation level, and performance

