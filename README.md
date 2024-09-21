# sql_zoo
My solutions to [sql zoo tutorials.](https://sqlzoo.net/wiki/SQL_Tutorial)

## Sections
0. [SELECT basics](https://sqlzoo.net/wiki/SELECT_basics)

    1. 
    ```sql
    SELECT population FROM world
    WHERE name = 'Germany'; 
    ```   
    2. 
    ```sql
    SELECT name, population FROM world 
    WHERE name IN ('Sweden', 'Norway', 'Denmark');
    ```
    3.
    ```sql
    SELECT name, area FROM world
    WHERE area BETWEEN 200000 AND 250000;
    ```