The MYSQL HR database project entails the development of a database aimed at managing data related to employees, departments, salaries, job titles, and departmental management within a company. This database comprises six tables: employees, departments, dept_emp, dept_manager, salaries, and titles.

The employees table is responsible for storing fundamental information about all employees, encompassing their personal details and hire dates. The departments table houses data regarding all company departments, including their respective department numbers and names. Linking employees to their respective departments and the duration of their tenure within those departments is the task of the dept_emp table. Meanwhile, the dept_manager table stores details concerning departmental managers and the duration of their incumbency. The salaries table keeps records of each employee's salary history, including salary amounts and corresponding time periods. Lastly, the titles table maintains information regarding job titles held by employees and the durations of those titles.

The project involves the formulation of various queries and modifications to the database. These tasks include adjusting the hire and birth dates of employees to different year ranges, determining the tenure of each department manager, calculating the number of employees supervised by each manager, and introducing new columns to certain tables.

This HR database project serves as a valuable tool for monitoring employee information and employment history within the company. It facilitates report generation and enables the analysis of employee data.

Database Description:
employees table:
Columns: emp_no (primary key), birth_date, first_name, last_name, gender, and hire_date.
This table contains comprehensive information about all company employees, covering personal details and hire dates.

departments table:
Columns: dept_no (primary key) and dept_name.
It stores data pertaining to all company departments, including department numbers and names.

dept_emp table:
Columns: emp_no, dept_no, from_date, and to_date.
This table links employees to their respective departments and records the duration of their tenure within those departments.

dept_manager table:
Columns: dept_no, emp_no, from_date, and to_date.
It stores information about departmental managers and the duration of their tenure in their managerial roles.

salaries table:
Columns: emp_no, salary, from_date, and to_date.
This table maintains records of each employee's salary history, including salary amounts and corresponding time periods.

titles table:
Columns: emp_no, title, from_date, and to_date.
It contains data regarding the job titles held by employees and the durations of those titles.





