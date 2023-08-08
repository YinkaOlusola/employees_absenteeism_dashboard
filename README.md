# Employees Absenteeism Dashboard

This Project was carried out as part of the requirements to complete the Data Science Programme at Explore AI Academy.
<br>
<br>
A manager at a medium-sized company had noticed a drop in performance from the  team. 
The causes were investigated and it was found out that absenteeism is quite a problem. There is a need to determine how to 
help those who are missing work. 
Human Resources Absenteeism dataset was provided and I was required to use this 
dataset to build a Power BI dashboard. This dashboard will then be used to gather insights and
answer questions regarding employee absenteeism.
<br>
<br>
The dataset was cleaned and wrangled on Power BI using DAX and the Dashboard was equally created.

The dataset contains two tables, the **Employee_info table**, and the **Absenteeism table**.

The description of the respective tables is given below:
<br>
<br>
<br>
### Employee_info

● **ID:** Unique identifier for each employee.

● **Transportation expense:** Transportation cost (in USD). 

● **Distance from residence to work:** The distance from the place of work and the employee’s place of residence (kilometers).

● **Age:** Age of the employee (years).

● **Education:** High school (1), graduate (2), postgraduate (3), master and doctorate (4).

● **Children:** Number of child dependents.

● **Social drinker:** Either “yes” (1) or “no” (0).

● **Social smoker:** Either “yes” (1) or “no” (0).

● **Pet:** The number of pets an employee has.

● **Weight:** The weight of the employee (in kilograms).

● **Height:** The height of the employee (in centimeters)
<br>
<br>
<br>
### Absenteeism
● **ID:** Unique identifier for each employee.

● **Reason for absence:** Incomplete submission, Family-related, Medical reasons, Unjustified leave 

● **Month of absence:** Month number of the year.

● **Day of the week:** Monday, Tuesday, Wednesday, Thursday, Friday.

● **Workload Average/day:** Average number of work tasks completed per day.

● **Hit target:** Target hit factor (0–100).

● **Disciplinary failure:** A failure to adhere to a previous disciplinary warning relating 
to absenteeism.

● **Absenteeism time in hours:** Number of hours the employee has been absent.

● **Service time:** Number of working hours produced by each employee.
<br>
<br>
<br>
## After Data Wrangling, the following were included:

● **Season** based on Month of absence;

● **BMI** based on Weight and Height;
<br>
<br>
<br>
## Important points raised about Absenteeism

● An employee may have **health-related** issues caused by an unhealthy lifestyle. 

● A younger, more inexperienced employee may be absent from work **after a social weekend**. Is there a pattern of absenteeism based on the **day of the week**?

● Does the distance an employee needs to **travel** to work affect their attendance?

● The season can affect attendance. Winter months might cause sickness or difficult travel conditions.
<br>
<br>
### The images below are from the dashboard that was created.
<br>
<br>

![page-1](https://github.com/YinkaOlusola/employees_absenteeism_dashboard/assets/52519547/ecf3d394-4b8a-4c04-922a-c8a8aa3c185f)
<br>
<br>
From the figure above, the highest number of hours of Absenteeism happens on Monday with most of the absenteeism coming from employees who are social drinkers. This could be as a result of a social weekend as suggested in the points raised above.
More so, most of the absenteeism is a result of medical reasons as shown above with social drinkers having the higher number. This may be a result of unhealthy lifestyles among these employees.
Additionally, July and March have the highest number of absenteeism which could be as a result of challenges faced due to weather or too much social activities.

<br>
<br>
<br>

![page-2](https://github.com/YinkaOlusola/employees_absenteeism_dashboard/assets/52519547/a02f03f9-c420-4fb0-af1b-18db0d4dbd5f)
<br>
<br>
The highest absenteeism was recorded in Spring followed by Winter. This could be a result of activities or constraints associated with these seasons. Additionally, when compared across age groups, it can be seen that the highest absenteeism was recorded among employees in their 30s with the highest number of social drinkers being among them. And this could be an indication of the influence of their life or lifestyle on their absenteeism.
The data equally showed that the highest absenteeism was recorded among employees with low levels of education.

<br>
<br>
<br>

![page-3](https://github.com/YinkaOlusola/employees_absenteeism_dashboard/assets/52519547/77cfde17-9ff4-4100-be54-294f6b07ae78)
<br>
<br>
Percentage absenteeism by education level and drinker status shows that employees with only High school education were absent the most and have the highest number of social drinkers. The Master/Doctorate with 100% social drinkers calls for a further investigation into the life of such employees but this data was not available at the time of this project.
Furthermore, March has the highest work hours and equally record the highest absenteeism, this could mean that employees are avoiding this high work rate and it is advisable to investigate further into this situation. This same situation can be observed in absenteeism by day of the week, where Monday has the highest Work hours and equally the highest absenteeism when compared with other days.
Much cannot be deduced from absenteeism by season and smoker status.
<br>
<br>
<br>

![page-4](https://github.com/YinkaOlusola/employees_absenteeism_dashboard/assets/52519547/4ed8e44d-3202-4cb3-a3e4-e1d2fbd3260f)
<br>
<br>
When compared across seasons, most employees recorded their highest absenteeism in spring.
Social drinkers can be seen to have the most absenteeism and most of them adhered to disciplinary actions.
