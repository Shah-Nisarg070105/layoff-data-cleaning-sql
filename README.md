📊 Layoff Dataset Cleaning using SQL
📌 Overview

This project focuses on cleaning and transforming a real-world layoffs dataset using SQL. The goal was to improve data quality, ensure consistency, and prepare the dataset for accurate analysis and insights.

🛠️ Tools & Technologies
SQL (MySQL / PostgreSQL / SQL Server)
Window Functions
Common Table Expressions (CTEs)
📂 Dataset
Contains 2000+ records of layoff data
Includes fields like company, industry, location, total layoffs, percentage layoffs, date, etc.
🚀 Key Objectives
Clean messy and inconsistent data
Handle missing (NULL) values
Remove duplicates and irrelevant records
Standardize formats across columns
Optimize schema for better performance
⚙️ Steps Performed
1. Data Cleaning
Removed duplicate records using ROW_NUMBER()
Trimmed and standardized text fields (company names, industries, locations)
Fixed inconsistent formats (e.g., date formats)
2. Handling Null Values
Identified missing values across columns
Imputed or removed NULL values based on relevance
Ensured no critical fields remained incomplete
3. Data Standardization
Unified inconsistent values (e.g., industry naming variations)
Normalized categorical data for better grouping and analysis
4. Data Transformation
Used CTEs for step-by-step transformations
Applied joins to enrich and refine dataset
Built a structured and analysis-ready dataset
5. Schema Optimization
Modified data types for efficiency
Removed unnecessary columns
Improved overall table structure
🧠 Key SQL Concepts Used
ROW_NUMBER() for duplicate removal
PARTITION BY for grouping operations
CTE (WITH clause) for modular queries
JOIN operations for data transformation
CASE WHEN for conditional logic
📈 Outcome
Cleaned and structured dataset ready for analysis
Improved data consistency and reliability
Reduced redundancy and optimized performance
