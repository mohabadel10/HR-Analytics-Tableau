# Employee Salary Analysis Dashboard

An interactive Tableau dashboard analyzing employee demographics, salaries, departments, occupations, age distribution, salary levels, and gender distribution.

## Live Dashboard

View the interactive dashboard on Tableau Public:

[Open the Employee Salary Analysis Dashboard](https://public.tableau.com/app/profile/mohab.adel/viz/ParksandRecreation_17890663854760/Dashboard1?publish=yes)

## Dashboard Preview

![Employee Salary Analysis Dashboard](images/employee-analysis-dashboard.jpg)

## Project Overview

This project analyzes employee information by combining three related tables:

1. Employee demographics
2. Employee salary information
3. Department names

The data was joined to create a unified dataset for analyzing salary patterns and employee characteristics across departments and occupations.

The dashboard was designed to demonstrate data preparation, calculated fields, parameters, interactive analysis, and dashboard storytelling using Tableau.

## Key Dashboard Metrics

The dashboard includes the following summary metrics:

- Total employees
- Average salary
- Median salary
- Average employee age

## Analysis Included

### Salary by Department

This bar chart compares salary information across departments.

A parameter allows the user to switch between:

- Average salary
- Total salary
- Employee count

This makes it possible to analyze departments from different perspectives instead of using only one fixed metric.

### Salary Compared with Department Benchmark

This view compares each employee's salary with the average salary of their department.

The comparison is displayed as a percentage:

- Positive percentages indicate that an employee earns more than the department average.
- Negative percentages indicate that an employee earns less than the department average.
- Percentages near zero indicate that the employee's salary is close to the department average.

### Salary Levels

Employees are grouped into three salary categories:

- High Salary
- Medium Salary
- Low Salary

This classification makes it easier to understand the distribution of employees across salary ranges.

### Top Occupations by Salary

This bar chart ranks occupations according to average salary.

A parameter allows the user to select the number of occupations displayed:

- Top 3
- Top 5
- Top 7
- Top 9

This parameter makes the dashboard more flexible and allows users to focus on different levels of the ranking.

### Employee Age Distribution

This chart shows how employees are distributed across age groups using age bins.

It helps identify the most common employee age ranges and provides a general view of the workforce's age structure.

### Gender Distribution

The donut chart shows the number of male and female employees in the dataset.

It provides a quick view of gender representation among the employees included in the analysis.

## Tableau Features Used

- Joining multiple tables
- Parameters
- Calculated fields
- Aggregations
- Average and median calculations
- Employee age bins
- Salary classification
- Department-level benchmarking
- Percentage variance analysis
- Top N filtering
- Bar charts
- Donut charts
- Interactive dashboard design

## Advanced Calculated Fields

The project uses calculated fields to support the analysis, including calculations for:

- Department salary benchmarks
- Salary variance percentages
- Salary-level classification
- Age groups
- Top occupation filtering
- Aggregated employee metrics

A department benchmark percentage can be represented conceptually as:

```text
(Employee Salary - Department Average Salary)
/
Department Average Salary
```

This calculation shows how much an employee's salary differs from the average salary in their department.

## Main Insights

The dashboard makes it possible to identify:

- Which departments have the highest average salary
- Which departments have the highest total salary
- How many employees work in each department
- Which occupations have the highest average salaries
- How individual salaries compare with department benchmarks
- How employees are distributed across salary levels
- The most common employee age groups
- The gender distribution of the workforce

## Tools Used

- Tableau
- Tableau Public
- Data modeling and table joins
- Calculated fields
- Parameters
- Data visualization
- Dashboard design

## Project Objective

The objective of this project was to build an interactive employee analytics dashboard that transforms multiple related tables into useful business insights.

The project demonstrates the ability to:

- Combine data from multiple tables
- Create meaningful calculated fields
- Build interactive Tableau dashboards
- Analyze salary and demographic data
- Present findings clearly to non-technical users

## Author

Mohab Adel

- Tableau Public: [View my Tableau profile](https://public.tableau.com/app/profile/mohab.adel)
- GitHub: https://github.com/mohabadel10
- LinkedIn: https://www.linkedin.com/in/mohab-adel10m/
