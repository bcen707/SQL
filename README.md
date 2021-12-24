# SQL
Query Construction


SELECT name, population, area
FROM world
WHERE area > 3000000 XOR population > 250000000;

SELECT name, population, area
FROM world
WHERE area > 3000000 OR population > 250000000;

SELECT name, population
FROM world
WHERE name IN ('France','Germany','Italy');

SELECT name, capital
FROM world
WHERE LENGTH(name) = LENGTH(capital);

SELECT name, capital
FROM world
WHERE LEFT(name, 1) = LEFT(capital, 1) AND name <> capital;

SELECT name 
FROM world
WHERE name LIKE '%a%'
  and name LIKE '%i%'
  and name LIKE '%i%'
  and name LIKE '%e%'
  and name LIKE '%o%'
  and name LIKE '%u%'
AND name NOT LIKE '% %';

SELECT name
FROM world
WHERE name LIKE 'Y%' 

SELECT name
FROM world
WHERE name LIKE '%land'

SELECT name
FROM world
WHERE name LIKE 'C%' AND name LIKE '%ia'



