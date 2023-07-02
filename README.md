# Analysing Employee's Performance for HR Analytics

Situation: A company wanted to measure their employee’s performance and reviews throughout the year.
They have collected a large dataset of no. of training given, employee ids, and length of services from the company’s database.
The company wants to identify common issues and areas of improvement to enhance its employee performance and overall employee satisfaction.

Dataset: Uncleaned_employees_final_dataset.csv

# Module 1: Data Processing using Python
Data Cleaning/Pre-Processing: The first step is to obtain clean and refined data for proper analysis for this the following steps were performed in order to obtain a clean dataset:
Removed duplicate rows.
Removed rows for which numeric columns are having irrelevant data type values
Removed irrelevant values from each column. Validated all values for a column, Checked for any inconsistencies or discrepancies in data types, units, or formats. 
Exported the cleaned dataset as a .csv file and converted it into a SQL file for retrieving useful information from the database using MySQL for further analysis.

File: Pre-Processing the data using Python.ipynb

# Module 2: Data Analysis using SQL
Task 1: Write an SQL query to solve the given problem statement.
Find the average age of employees in each department and gender group. ( Round average age up to two decimal places if needed)
![238145264-af49e614-a107-4f8b-8a59-e4f206272d48](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/a1a25ce3-e615-47cc-9124-582c8870acb0)

Task 2: Write an SQL query to solve the given problem statement. 
List the top 3 departments with the highest average training scores. ( Round average scores up to two decimal places if needed)
![2](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/6c6578ce-5e77-4146-b197-2fbd0504eba7)

Task 3: Write an SQL query to solve the given problem statement.
Find the percentage of employees who have won awards in each region. (Round percentages up to two decimal places if needed)
![3](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/8355a92b-81fa-4378-908f-0cb47de0079f)

Task 4: Write an SQL query to solve the given problem statement. 
Show the number of employees who have met more than 80% of KPIs for each recruitment channel and education level.
![4](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/db190650-4e18-4620-a592-807539f86430)

Task 5: Write an SQL query to solve the given problem statement. 
Find the average length of service for employees in each department, considering only employees with previous year ratings greater than or equal to 4. ( Round average length up to two decimal places if needed)
![5](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/4fead804-e5a2-4da7-94ae-0abab23b90e4)

Task 6: Write an SQL query to solve the given problem statement. 
List the top 5 regions with the highest average previous year ratings. ( Round average ratings up to two decimal places if needed)
![6](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/9f832c10-b1a7-40f1-ba42-e4ba16673f2a)

Task 7: Write an SQL query to solve the given problem statement. 
List the departments with more than 100 employees having a length of service greater than 5 years.
![7](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/c41423d0-594e-4865-8113-9987819fd3d0)

Task 8: Write an SQL query to solve the given problem statement.
Show the average length of service for employees who have attended more than 3 trainings, grouped by department and gender. ( Round average length up to two decimal places if needed)
![8](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/ef083b4b-6516-4eaf-b8fe-48c855d67ba5)

Task 9: Write an SQL query to solve the given problem statement. 
Find the percentage of female employees who have won awards, per department. Also show the number of female employees who won awards and total female employees. ( Round percentage up to two decimal places if needed)
![9](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/7bd4cd1e-5d15-40ae-827f-19b708b7b48e)

Task 10: Write an SQL query to solve the given problem statement.
Calculate the percentage of employees per department who have a length of service between 5 and 10 years. ( Round percentage up to two decimal places if needed)
![10](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/cc22d65d-8370-4b05-93fd-9301a59da5ff)

Task 11: Write an SQL query to solve the given problem statement.
Find the top 3 regions with the highest number of employees who have met more than 80% of their KPIs and received at least one award, grouped by department and region.
![11](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/e8a3517a-f1f2-447e-a331-400b99a07594)

Task 12: Write an SQL query to solve the given problem statement.
Calculate the average length of service for employees per education level and gender, considering only those employees who have completed more than 2 trainings and have an average training score greater than 75 ( Round average length up to two decimal places if needed)
![12](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/f9307fb3-30b2-483f-aa0e-90fe8c989e53)

Task 13: Write an SQL query to solve the given problem statement.
For each department and recruitment channel, find the total number of employees who have met more than 80% of their KPIs, have a previous_year_rating of 5, and have a length of service greater than 10 years.
![13](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/ee4c0b5a-a4c6-40f1-bd32-0bb1f174995c)

Task 14: Write an SQL query to solve the given problem statement.
Calculate the percentage of employees in each department who have received awards, have a previous_year_rating of 4 or 5, and an average training score above 70, grouped by department and gender ( Round percentage up to two decimal places if needed).
![14](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/e4155060-e61b-48a6-818c-52019ca5c5d2)

Task 15: Write an SQL query to solve the given problem statement. 
List the top 5 recruitment channels with the highest average length of service for employees who have met more than 80% of their KPIs, have a previous_year_rating of 5, and an age between 25 and 45 years, grouped by department and recruitment channel. ( Round average length up to two decimal places if needed).
![15](https://github.com/Jeswin21/Analysing-Employees-Performance-for-HR-Analytics/assets/85884215/bcc2c87b-91d1-42c1-b4ad-8426f2807917)




