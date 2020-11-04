# datacamp-
solution for sql course of datacamp
Introduction to SQL Server
-- started from here--
1. SELECTion Box
</> Simple selections
ex ;SELECT the country column FROM the eurovision table.
SELECT country
FROM eurovision;

country
Israel
France
Sweden
Croatia
...

ex ; Amend your query to return the points column instead of the country column.
SELECT 
  points 
FROM 
  eurovision;

points
53
107
33
45
...


ex;Use TOP to change the existing query so that only the first 50 rows are returned.

SELECT 
  TOP (50) points 
FROM 
  eurovision;

points
53
107
33
45
...



