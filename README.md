# Pewlett Hackard Analysis (Module 7 Challenge)
## Overview of Analysis
The Pewlett Hackard company has requested an audit of their employees in order to determine the number of employees who are at or near retirement age in order to determine what next steps the organization should take. Early analysis shows that more than 40,000 employees are near retirement age.  This incited the company to request further analysis into the data to help guide their decisions for next steps.
## Results
### Point 1
The first result was to create a list of all the job titles held by people of retirement age and to count the number of potential retirees will be vacating each title in the next few years.
![Number of Titles of Retirement Age](http://url/to/img.png)
### Point 2
Reviewing the data from Point 1, one can conclude that Senior Engineers and Senior Staff are the two most common titles by far where people will be retiring by a ratio of 2:1 among all other titles.  Managers will be least affected with only two employees nearing retirement age with that title.
### Point 3
When considering positions, employees need to 
### Point 4
image?
## Summary
Based on these restults, the following queries were considered below.
### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
The number of roles that will need to be filled, based on the search of titles, is 72,458
### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
The number of qualified, retirement-ready employees in the company who are ready to mentor the next generation for each relevant job title include the following:
#### Senior Engineer: 393
#### Senior Staff: 318
#### Engineer: 308
#### Staff: 406
#### Technique Leader: 77
#### Assistant Enginner: 47
#### Manager: 0

### Additional query #1: What would be the ratio of mentors to vacant positions, assuming all positions were vacated at once?
#### Senior Engineer: 393:25916 (roughly 66 new hires to 1 mentor)
#### Senior Staff: 318: 24926 (roughly 78:1)
#### Engineer: 308: 9285 (roughly 30:1)
#### Staff: 406: 7636 (roughly 19:1)
#### Technique Leader: 77 : 3603 (roughly 47:1)
#### Assistant Enginner: 47: 1090 (roughly 23:1)
#### Manager: 0:2 

### Additional query #2: How much would the employee pool for mentors expand if the age requirements were expanded from a single year (1965) to include 1964 to 1970?
This would expand the number of employees from roughly 1500 employees to 1900 employees.  This was ascertained using the following code:
![Number of Potential Mentors Born Between 1964 and 1970](http://url/to/img.png)
