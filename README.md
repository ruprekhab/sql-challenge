# Overview
This activity is divided into three main parts: Data Modeling, Data Engineering, and Data Analysis. The goal is to model data from CSV files, create SQL table schemas, and perform various data queries for insightful analysis. 

## Data Modeling
The six CSV files for the project are provided in the EmployeesSQL folder. After inspecting the CSV files, an Entity Relationship Diagram of the tables has been sketched using “https://www.quickdatabasediagrams.com/"
![image_alt](https://github.com/ruprekhab/sql-challenge/blob/main/EmployeeSQL/ERD1.png)

## Data Engineering
Using the information provided a  table schema has been created for each of the six csv files. Each of the tables include a primary key, foreign keys, composite key (when necessary), datatype and other constraints. After creating the tables, the csv files have been imported into its corresponding SQL table.
![image_alt](https://github.com/ruprekhab/sql-challenge/blob/main/EmployeeSQL/sql_challenge.png)

## Data Analysis
Sql queries were executed to retrieve the required data analysis:
* List each employee's employee number, last name, first name, sex, and salary.
* List the first name, last name, and hire date of employees hired in 1986.
* List the manager of each department, along with their department number, department name, employee number, last name, and first name.
* List the department number and department name for each employee, along with their employee number, last name, and first name.
* List first name, last name, and sex of employees with the first name "Hercules" and a last name starting with "B".
* List each employee in the Sales department, including their employee number, last name, and first name.
* List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
* List the frequency counts of all employee last names in descending order.
