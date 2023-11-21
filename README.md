### Case Statement
1. Display all Bollywood movies, and calculate the profit made. Display the highest profit first.


> SQL Query:
>![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/ce5f002d-03b7-47a3-bc09-9b819f84cc10)

 Using case statement to normalize all values to a single unit - Millions
> Output:
> ![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/6daed3fc-f520-4f47-b6df-b54017a89c43)

### Joins & Group Concat
2. Print actor names, movie names they have acted in separated by a pipe, and the number of movies they have acted in.

![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/2fc0c123-b68d-4903-b932-5eb1f7a9d533)

   We need to join 3 tables.

> SQL Query:
> ![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/b57574cf-ffc5-44e6-b74f-08aac934b566)

Using GROUPBY to CONCAT the column values.
> Output:
> ![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/e0081927-37e2-4ffb-8398-cdfa678a6251)

### SubQuery
3. Print details of Movies with maximum and minimum IMDb rating.

> SQL Query:
>![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/83c85202-19f5-40c3-afbc-866c9d521f84)

> Output:
> ![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/141f9c08-0e6a-4117-9e89-03e7803fc85e)

### SubQuery - Returns a table
4. Select all the actors whose age is greater than 70 and less than 85

> SQL Query:
>![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/6a1bb401-212c-419d-983e-f4dcd500e1b1)


> Output:
> ![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/e8402fb3-7a20-4e59-aa21-56f0400c88e5)

5.  For every actor, display the actor_id and movie count
Using a correlated subquery:
 A subquery (a query nested inside another query) that uses values from the outer query. Because the subquery may be evaluated once for each row processed by the outer query, it can be slow.

> SQL Query:
> ![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/646dcb9c-32c2-441d-b4ae-bc12d2c20d9f)

> Output:
> ![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/207f4cba-a49a-446b-863c-7ef592c4283c)

Using CTE

> SQL Query:
> ![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/a229d334-9515-4445-ba06-ab6299e2f8ac)

> Output:
> ![image](https://github.com/mythilyram/Movies-SQL/assets/123518126/4f97d464-c5e1-4637-a4ce-7d8594b8bf7a)
