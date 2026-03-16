# HR_Analytics_Power_BI_project
This project focuses on analyzing employee data using Power BI to understand workforce trends, employee attrition, and organizational patterns.

The dashboard provides HR teams with interactive visualizations and insights that help in identifying the major factors responsible for employee turnover and improving workforce management.

This project was developed with reference to the HR Analytics project by Rishabh Mishra, which served as a learning guide for building the dashboard and structuring the analysis.

**Objectives**

Analyze employee attrition trends
Identify departments with high employee turnover
Understand the relationship between salary, experience, and attrition
Provide HR teams with interactive dashboards for better decision making
Identify workforce patterns that affect employee retention

***Tools & Technologies Used***

**Power BI**  – Dashboard development and data visualization

**Power Query** – Data cleaning and transformation

**DAX (Data Analysis Expressions)** – Creating calculated columns and measures

**CSV Dataset** – Source data for analysis


**Dataset Description**



| Column           | Description                           |
| ---------------- | ------------------------------------- |
| Age              | Age of the employee                   |
| Attrition        | Whether the employee left the company |
| Department       | Department of the employee            |
| Education        | Education level                       |
| Gender           | Male / Female                         |
| Job Role         | Position in the organization          |
| Monthly Income   | Salary of the employee                |
| Job Satisfaction | Satisfaction score                    |
| Years at Company | Total years employee worked           |

**The dashboard highlights the following HR metrics**:

Total Employees

Attrition Count

Attrition Rate (%)

Average Age

Average Salary

Average Years at Company

**Major Insights**

**1. Sales Department Has the Highest Attrition**

The Sales department shows the highest employee turnover compared to other departments.

**2. Employees with Lower Salaries Leave More Frequently**

Employees with lower monthly income tend to have higher attrition rates.

**3. Early Career Employees Show Higher Attrition**

Most employees leaving the organization have 1–3 years of experience, indicating higher turnover in early career stages.

**4. Certain Job Roles Have Higher Turnover**

Roles such as Sales Executive and Laboratory Technician have the highest attrition.

**5. Younger Workforce Has Higher Attrition**

Employees in the 26–35 age group represent the majority of attrition cases.

**6. Job Satisfaction Influences Retention**

Employees with low job satisfaction levels are more likely to leave the company.

**Business Recommendations**

Based on the insights obtained from the analysis, the following recommendations can help reduce attrition:
Improve employee engagement programs in high-attrition departments.
Provide career growth opportunities for employees in their early years.
Review salary structures for roles with high attrition.
Conduct regular employee satisfaction surveys.
Implement mentorship and training programs to improve retention.

**Dashboard Features**

The Power BI dashboard includes the following interactive visuals:

Employee Attrition Overview

Department-wise Attrition Analysis

Salary Distribution

Job Role Attrition Analysis

Employee Demographics

Job Satisfaction Analysis

Interactive Filters and Slicers

These features allow HR teams to explore the data dynamically and identify workforce trends quickly.

**DAX Measures Used**

Some of the important DAX measures used in this project include:

**Attrition Count**

Attrition Count = CALCULATE(COUNT(Employee[EmployeeID]), Employee[Attrition] = "Yes")

**Attrition Rate**

Attrition Rate = DIVIDE([Attrition Count], COUNT(Employee[EmployeeID])) * 100

**Average Salary**

Average Salary = AVERAGE(Employee[MonthlyIncome])

**Average Age**

Average Age = AVERAGE(Employee[Age])

# Project Structure

HR-Analytics
│
├── HR Analytics.csv
├── HR Analytics_Dashboard.pbix
└── README.md

**Dashboard Screenshots**

(Add screenshots of your Power BI dashboard here)



# Conclusion #

This HR Analytics dashboard demonstrates how data visualization and analytics can help HR departments understand employee behavior, identify attrition patterns, and make data-driven workforce decisions.

The project showcases the practical use of Power BI, data transformation, and DAX calculations for solving real-world HR business problems.
