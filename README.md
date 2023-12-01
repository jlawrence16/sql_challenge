# sql_challenge

In this exercise, I was tasked with a research project about people whom the company employed during the 1980s and 1990s. 
All that remains of the employee database from that period are six CSV files.

I designed the tables to hold the data from CSV files, imported the CSV files into a SQL database, and then answer questions about the data.

Data Modeling
I inspected the CSV files, and then sketched an Entity Relationship Diagram of the tables.

Data Engineering
I used the provided information to create a table schema for each of the six CSV files. 
I specified the data types, primary keys, foreign keys, and other constraints and then imported each CSV file into its corresponding SQL table.

Data Analysis

I wrote SQL queries to answer the following reaearch questions, making use of joins and aggregation.

List the employee number, last name, first name, sex, and salary of each employee.

List the first name, last name, and hire date for the employees who were hired in 1986.

List the manager of each department along with their department number, department name, employee number, last name, and first name.

List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

List each employee in the Sales department, including their employee number, last name, and first name.

List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
