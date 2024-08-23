# Employee Attrition Analysis

## Table of Contents
- Project Overview
- Data Description
- Data Extraction and Loading
- Data Analysis
- Results
- Technologies Used
- Setup Instructions

## Project Overview
This project involves analyzing employee attrition data using PySpark within Databricks. The objective is to gain insights into factors affecting employee attrition, including age, department, education level, environment satisfaction, and business travel.

## Data Description
The dataset used in this project is a CSV file containing information about employee attrition. Key fields include:

- **EmployeeCount:** Number of employees
- **Attrition:** Whether the employee left the company (Yes/No)
- **Age:** Age of the employee
- **Department:** Department where the employee works
- **Education:** Level of education of the employee
- **EnvironmentSatisfaction:** Satisfaction level with the work environment
- **BusinessTravel:** Frequency of business travel

## Data Extraction and Loading
The data extraction and loading process is implemented in Databricks using PySpark. This includes:

- **Extraction:** Loading data from the CSV file located at `/FileStore/tables/employee_attrition.csv`.
- **Loading:** Creating a temporary SQL view for enabling SQL queries and analysis.

## Data Analysis
The analysis involved several key steps:

- **Total Employee Count:** Calculated the total number of employees in the dataset.
- **Attrition Count:** Aggregated data to find the number of employees who left the company, segmented by attrition status.
- **Attrition by Age Group:** Analyzed the number of employees who left the company, segmented by age groups.
- **Attrition by Department:** Investigated the distribution of employee attrition across different departments.
- **Attrition by Education Level:** Calculated the number of employees who left the company, segmented by education level.
- **Attrition by Environment Satisfaction:** Analyzed the number of employees who left the company based on their satisfaction with the work environment.
- **Attrition by Business Travel:** Examined the number of employees who left the company based on their frequency of business travel.

## Results
Key insights obtained from the analysis include:

- Employees aged between 26-32 are most likely to leave the organization.
- The Research and Development department has the highest attrition rate.
- 41.1% of employees with a bachelor’s degree left the organization.
- 72 employees who reported low environment satisfaction left the organization.
- 156 employees who traveled rarely left the organization.

## Technologies Used
- **Databricks:** Cloud-based data analytics platform.
- **PySpark:** Python API for Apache Spark.
- **Spark SQL:** SQL querying on large datasets.
