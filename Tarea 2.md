## Temas Selectos de Estadística | María Fernanda López
SQL Practice Lesson 10 | Tarea 2

1. **Find the longest time that an employee has been at the studio** 

|| SELECT 

MAX (Years\_employed)

FROM employees;

1. **For each role, find the average number of years employed by employees in that role**

|| SELECT Role, AVG(Years\_employed)

FROM employees

GROUP BY Role;

1. **Find the total number of employee years worked in each building**
**
` `|| SELECT Building, SUM(Years\_employed)

FROM employees

GROUP BY BUILDING;


![OXXO | Uso Interno](Aspose.Words.dc40af9a-a6cd-4a59-9739-ad6968bbc839.001.png)
