# EMPLOYEE-ATTRITION-PERFORMANCE-ANALYSIS

Leveraging Tableau descriptive and diagnostic analytics in understanding the demographic and job related factors driving employee turnover.
---
![image](https://private-user-images.githubusercontent.com/173513243/381237109-c9541fea-4fb6-434c-b218-dfe2d76ed66c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDY0NjE3ODMsIm5iZiI6MTc0NjQ2MTQ4MywicGF0aCI6Ii8xNzM1MTMyNDMvMzgxMjM3MTA5LWM5NTQxZmVhLTRmYjYtNDM0Yy1iMjE4LWRmZTJkNzZlZDY2Yy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTA1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUwNVQxNjExMjNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lZmM3MTZiMWIzYmUzNzQzNjcyNDYyNjFhM2EzN2E4Mjg0NWFjMzRjYzhjZDdjYzJiZjlhZDBjY2QwZmQxMWI0JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.q5BSFAVtsgkPU5Em89ru7XsQvbNR0BE9BaP4Z-debUA)

*Disclaimer⚠️: All datasets, slides and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual. All info are dummy and design to demonstrate my capabilities of using Tableau to perform descriptive and diagnostic analytics.*

INTRODUCTION 
--- 
Talent-Pulse Solutions Inc. is a forward-thinking organization dedicated to empowering businesses through strategic workforce management. As a leader in talent optimization, the company prides itself on fostering an environment where employees can thrive. However, recent challenges with employee retention and workforce engagement have highlighted the need for actionable insights. By leveraging data analytics and visualization, Talent-Pulse aims to uncover key trends, optimize employee satisfaction, and enhance overall organizational performance using Tableau. 

![image](https://private-user-images.githubusercontent.com/173513243/371840960-f15eda55-9fc7-4680-82bf-618dea318c7b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDY0NjIzMjUsIm5iZiI6MTc0NjQ2MjAyNSwicGF0aCI6Ii8xNzM1MTMyNDMvMzcxODQwOTYwLWYxNWVkYTU1LTlmYzctNDY4MC04MmJmLTYxOGRlYTMxOGM3Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTA1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUwNVQxNjIwMjVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lYWU0MDliZTdmNzY4ODJiYzQ0OWVmZDA4NjNhZGJjZWY0ODI4NTk4Yjg0NzgzOTBkNjYxYmNkOWRjY2ZkYmIxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Js1Fyg_fKnjt2nK9S4o0JhUJjKr_HBdkWU_YyhxRT6U)

PROBLEM STATEMENT
--- 
High attrition rates have been observed, which could impact productivity and organizational performance. Lack of clear understanding of attrition trends across departments, demographics, and tenure. Difficulty in identifying factors influencing recent attrition and low survey scores. Need for better visualization of workforce data to support decision-making.

AIM OF PROJECT 
--- 
* Identify key trends and factors contributing to employee attrition.
* Analyze workforce demographics by department, gender, age group, and education level to understand patterns.
* Track attrition trends over time and compare survey scores with employee turnover rates.
* Build a comprehensive dashboard to enable HR teams to make data-driven decisions.

SKILLS AND CONCEPT DEMONSTARTED 
--- 
* Business Understanding
* Data understanding & preparation
* Data import into Tableau
* Create calculated fields and bulid visualizations
* Interactive Dashboard
* Data Storytelling

MODELLING 
---
I conducted comprehensive data cleaning by using filter functions to eliminate null values and ensuring proper formatting of each column (Date, Text, Number) to support accurate analysis.The data model consists of a main table, Employees Info, which includes fields such as (Age, Dept, Gender and so on). By having all these info, we can conduct comprehensive analyses to better understand employee attrition and retention at company level. 

<img width="860" alt="image" src="https://github.com/user-attachments/assets/d1cc4407-6689-4f4a-873a-29bcdfe55aaa" />

VISUALIZATION
---
* Bar Chart 
* Gantt Bar
* Line Chart
* Donut/Pie Chart 
* Heat Map 

DATA ANALYSIS
---
### KPIs 
This visualization presents key performance indicators (KPIs) for Attrition Rate, Total Attrition, and Total Number of current employees at Talent-Pulse Solutions Inc.

<img width="205" alt="image" src="https://github.com/user-attachments/assets/ca7c88e5-adc9-4f4a-a081-342e4bde4856" />

Bar Chart
---
This bar chart compares age by category amongst all the current employees, highlighting majority of their employees are in the age bracket of 25-34. While the least is from age 55 upwards. This could be because the company is seeking fresh minds and new talents to keep the organisation running as the younger generation will be in line with the latest technologies such as AI etc. 

<img width="553" alt="image" src="https://github.com/user-attachments/assets/5c981b1e-8505-44c3-bf2b-1cf8f42e904e" />

Line Chart 
---
This chart visualizes the yearly trends of employees who leaves company year on year. It highlights periods where employee resignations exceed or fall below their respective averages. This visualization shows that most employees leave between 0-6 months after joining which is a high turnover rate. This could be beacuse of lack of work life balance, low pay etc. 

<img width="674" alt="image" src="https://github.com/user-attachments/assets/196cfd15-f648-4085-b46f-482c66a1751e" />

Heat Map
---
The heatmap in the image shows job roles along the y-axis and satisfaction levels (1 to 4) along the x-axis. Darker colors represent higher counts of responses at a given satisfaction level. The Laboratory Technician role stands out with the highest number of responses (20) in satisfaction level 1, and although there are some responses in levels 3 (21) and 4 (13), the count in level 1 is the highest of any role. However, Human Resources also shows a relatively high number (5) in level 1 and very low counts in higher levels.

![image](https://github.com/user-attachments/assets/367e22bf-6541-4453-9b19-141670ac8086)

Dashboard Overview 
--- 
The dashboard provides a comprehensive analysis of employee attrition performance over a period of time. 

<img width="781" alt="image" src="https://github.com/user-attachments/assets/33b08cd2-6fbf-4914-b4f7-a37102b6d5f5" />

RECOMMENDATIONS
---
* Offer career growth by creating clear career paths and internal promotion opportunities also support skill development through training, courses, and certifications.
* Review compensation & benefits by ensuring pay is competitive in your industry and region and offer attractive benefits (healthcare, PTO, flexibility, bonuses).
* Promote positive work life balance by giving employees reasonable amount of time off to spend time with families and travel and also offer hybrid working model.
* Monitor employee engagement with use of surveys to check job satisfaction regularly with that, company can act quickly on negative feedback.

These recommendations aim to reduce employee attrition by focusing on career growth, salaries, and positive work life balance going forward.

THANK YOU
---

For more information, you can contact me

![Orange Modern Technology LinkedIn Banner](https://github.com/user-attachments/assets/4d91e1e5-c613-48a0-8a9a-15dbaf997908)









  
