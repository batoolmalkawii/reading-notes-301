# Explore the Tech!
In today's blog, I am going to discuss some topics related to _web development_. So, _let's get started!_

## What is SQL?
SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.
And due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.

***There are many popular SQL databases including SQLite, MySQL, Postgres, Oracle and Microsoft SQL Server.
All of them support the common SQL language standard, which is what this site will be teaching, but each implementation can differ in the additional features and storage types it supports.***

## Relational databases
A relational database represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns 
(the attributes or properties of the table) and any number of rows of data.


- By learning SQL, the goal is to learn how to answer specific questions about this data, like "What types of vehicles are on the road have less than four wheels?"
or "How many models of cars does Tesla produce?", to help us make better decisions down the road.

- __SELECT__ statements, which are often colloquially refered to as queries. A query in itself is just a statement which declares what data we are looking for,
  where to find it in the database, and optionally, how to transform it before it is returned.
    - EX: Select query for a specific columns
SELECT column, another_column, …
FROM mytable;

    - EX: Select query for all columns
SELECT * 
FROM mytable;

- __Queries with constraints__
  - Select query with constraints
SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;
    
    
    - =, !=, < <=, >, >=	Standard numerical operators
    - BETWEEN … AND …	Number is within range of two values (inclusive)
    - NOT BETWEEN … AND …	Number is not within range of two values (inclusive)
    - IN (…)	Number exists in a list
    - NOT IN (…)	Number does not exist in a list
    - =	Case sensitive exact string comparison (notice the single equals)
    - != or <>	Case sensitive exact string inequality comparison
    - LIKE	Case insensitive exact string comparison
    - NOT LIKE	Case insensitive exact string inequality comparison
    - %	Used anywhere in a string to match a sequence of zero or more characters (only with LIKE or NOT LIKE)
    - _	Used anywhere in a string to match a single character (only with LIKE or NOT LIKE)
    - IN (…)	String exists in a list
    - NOT IN (…)	String does not exist in a list
 
 ------------
 ###  Filtering and sorting Query results:
  - Since the DISTINCT keyword will blindly remove duplicate rows, we will learn in a future lesson how to discard duplicates based on specific columns using grouping and the GROUP BY clause.
  - Another clause which is commonly used with the ORDER BY clause are the LIMIT and OFFSET clauses, which are a useful optimization to indicate to the database the subset of the results you care about.
The LIMIT will reduce the number of rows to return, and the optional OFFSET will specify where to begin counting the number rows from.

### Multi-table queries with JOINs:  
  - Using the JOIN clause in a query, we can combine row data across two separate tables using this unique key. The first of the joins that we will introduce is the INNER JOIN.
  ---------
  ### OUTER JOINs:
   - Depending on how you want to analyze the data, the INNER JOIN we used last lesson might not be sufficient because the resulting table only contains data that belongs in both of the tables.

If the two tables have asymmetric data, which can easily happen when data is entered in different stages, then we would have to use a LEFT JOIN, RIGHT JOIN or FULL JOIN instead to ensure that the data you need is not left out of the results.
------------
### NULLs
- NULL values in an SQL database. It's always good to reduce the possibility of NULL values in databases because they require special attention when constructing queries, constraints 

