## Temas Selectos de Estadística | María Fernanda López
SQL Practice Lesson 5 | Tarea 1

1. **List all the Canadian cities and their populations**

|| SELECT city, population FROM north\_american\_cities

WHERE country="Canada";

1. **Order all the cities in the United States by their latitude from north to south**

|| SELECT city FROM north\_american\_cities

WHERE country="United States"

ORDER BY latitude DESC;

1. **List all the cities west of Chicago, ordered from west to east**

|| SELECT \* FROM north\_american\_cities

WHERE longitude <-87.629798

ORDER BY longitude ASC;

1. **List the two largest cities in Mexico (by population)**

|| SELECT \* FROM north\_american\_cities

WHERE country="Mexico"

ORDER BY population DESC

LIMIT 2;

1. **List the third and fourth largest cities (by population) in the United States and their population**

|| SELECT \* FROM north\_american\_cities

WHERE country="United States"

ORDER BY population DESC

LIMIT 2 OFFSET 2;



![OXXO | Uso Interno](Aspose.Words.922c118e-3c6e-47b2-b09e-7b2de795399b.001.png)
