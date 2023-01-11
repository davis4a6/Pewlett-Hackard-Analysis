## Pewlett-Hackard Analysis
# Purpose
The purpose of this analysis was to help the manager at Pewlett-Hackard prepare for their upcoming "Silver Tsunami." The "Silver Tsunami" stems from the company having a large amount of employees that are expected to retire soon. Pwelett-Hackard's goal is to offer a retirement package for those who meet criteria as well as prepare to fill upcoming position vacancies. 

# Results
The four major things the manager needs from these two analyses and deliverables are:
1. To identify the retiring employees by their title.
2. To determine the number of titles filled by employees who are retiring.
2. To identify the employees that are eligible for participation in the mentorship program.
4. To determine the number of roles to fill by title and department.

Background
In this analysis, QuickDBD and Schemas were used to design databases and SQL queries to answer questions for Pwelett-Hackard's company. PostreSQL and pgAdmin were also used to load and build the company's data.

ERD 
The entity-relationship diagram (ERD) was used in PostreSQL to design the database table relationships. This acts as a blueprint for the design of the database.

![Alt text](file:///c%3A/Users/Ariana%20Davis/Desktop/Homework/Pewlett-Hackard-Analysis/EmployeeDB.png)


1. List of Employees Retiring by Title
This list of retiring employees contains the employee number, first name, last name, and title for all employees born in 1952. 
This list has some duplicates because there are some employees who have changed postions and departments over the years.

Reitrement Titles Table (csv file in data folder)
![Alt text](file:///c%3A/Users/Ariana%20Davis/Desktop/Homework/Pewlett-Hackard-Analysis/Retirement%20Titles.PNG)


2. List of Employees Retiring by Most Recent Title 
This list contains the employee number, first name, last name, title, their from date as well as their to date. 
This list also contains the latest titles that the potential retiree held.
Lastly, this list contains no duplicates. It shows the retirees' latest postion.

Unique Titles Table (csv file in data folder)
![Alt text](file:///c%3A/Users/Ariana%20Davis/Desktop/Homework/Pewlett-Hackard-Analysis/Unique%20Titles.PNG)

3. This table gives us more insight into the number of postions that will be open within the next few years for each title. It contains the employees' titles and the sum of each title. 

Count of Retirees Grouped by Title
![Alt text](file:///c%3A/Users/Ariana%20Davis/Desktop/Homework/Pewlett-Hackard-Analysis/Count%20of%20Retirees%20by%20Dept.PNG)

4. Lastly, we determined who might be eligible for the mentorship program. In this query, we collected 1940 records of employees who are eligible for a mentorship program. This was done based on upcoming retirees born in 1965.  

Employees Eligible for the Mentorship Program
![Alt text](file:///c%3A/Users/Ariana%20Davis/Desktop/Homework/Pewlett-Hackard-Analysis/mentorship%20eligible.PNG)

# Summary
Overall, the information that we have gathered suggests that the number of positions opening as a result of the Silver Tsunami are great. There are 90,398 employees that will be expected to retire in the upcoming years. This suggests that the company, Pewlett-Hackard, has some planning to do for their future.
The numbers show that there are enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett-Hackard employees.

ADDITIONAL TABLES

This additional table shows the number of employees that will be eligible for mentorship grouped by title. This will be helpful for the HR manager to see how many vacancies for each title will be coming up. This could be helpful to see if those employees will want to be a mentor, and while thinking of strategies to hire new employes in each respective field.

Number of employees that are eligible for mentorship grouped by title
![Alt text](file:///c%3A/Users/Ariana%20Davis/Desktop/Homework/Pewlett-Hackard-Analysis/mentorship%20eligible.PNG)