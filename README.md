# SQL_Mastery
This project aims to encompass most core tasks in SQL for data analysis. 

## Quick Links
- Jupyter notebook with SQL queries: [Notebook](SQL_Mastery.ipynb)
- Other projects I have made: [Portfolio Website](https://lucashoffschmidt.github.io/)

## Technologies Used
- **JupyterLab**: For running and documenting SQL queries. 
- **SQLite3**: Used to make a local relational database.
- **JupySQL**: Used to write inline SQL queries.
- **SQL**: Used to create database queries. 

## Process
  - Installed and loaded jupysql and connected to the local sqlite database.
  - Created tables for departments, employees, projects, assignments and salaries.
<img src="images/create_table.jpg" alt="Creating employees table" width="600">

  - Inserted data into the tables.
<img src="images/insert_into.jpg" alt="Inserting into employees table" width="600">

  - Investigated employees using queries
<img src="images/where.jpg" alt="Employees with department id 2" width="400">
<img src="images/group.jpg" alt="Total hours worked on projects with name starting with new" width="600">
<img src="images/left_join.jpg" alt="Employees that aren't assigned to any project" width="450">
<img src="images/double_join.jpg" alt="Employees' assigned project and assignment id" width="500">
<img src="images/union_all.jpg" alt="Employee with lowest salary compared to employee with highest salary" width="700">
<img src="images/subquery.jpg" alt="Department id, name and salary of each department head" width="500">
<img src="images/coalesce.jpg" alt="Employees' salary with missing salaries substituted with 0" width="600">
<img src="images/case_when.jpg" alt="Employees classified into groups based on their project hours" width="550">
<img src="images/CTE.jpg" alt="Employees that have worked more than 15 hours on their assigned project" width="600">
<img src="images/window.jpg" alt="Employees' salary change each year" width="500">
