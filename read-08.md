# Summary class 08

SQL: Structured Query Language.

to retrive the data from SQL you need to use SELECT statments.
- SELECT nameColumn FROM nameOfTable;
- SELECT nameColumn,another_column FROM nameOfTable;
- SELECT * FROM nameOfTable;  **to select all elements in table**

we used WHERE statmnt for filter the data
- SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;

Operator  | 	SQL Example
-------|----------
=, !=, < <=, >, >= | col_name != 4
BETWEEN … AND … | col_name BETWEEN 1.5 AND 10.5
NOT BETWEEN … AND | col_name NOT BETWEEN 1 AND 10
IN (…) | col_name IN (2, 4, 6)
NOT IN (…) | col_name NOT IN (1, 3, 5)
= | col_name = "abc"
!= or <> | 	col_name != "abcd"
LIKE | 	col_name LIKE "ABC"
NOT LIKE | 	col_name NOT LIKE "ABCD"
% | col_name LIKE "%AT%" (matches "AT", "ATTIC", "CAT" or even "BATS")
_ | col_name LIKE "AN_" (matches "AND", but not "AN")

the DISTINCT keyword will blindly remove duplicate rows
- SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC //ASC for alphabet order 
LIMIT num_limit OFFSET num_offset;

***schema*** is what describes the structure of each table, and the datatypes that each column of the table can contain.
- to insert new data we will use INSERT
INSERT INTO mytable
(column, another_column, …)
VALUES (value_or_expr, another_value_or_expr, …),
      (value_or_expr_2, another_value_or_expr_2, …),
      …;

- to update on the information of table
UPDATE mytable
SET column = value_or_expr, 
    other_column = another_value_or_expr, 
    …
WHERE condition;

- to create table
CREATE TABLE IF NOT EXISTS mytable (
    column DataType TableConstraint DEFAULT default_value,
    another_column DataType TableConstraint DEFAULT default_value,
    …
);

- we can use DELET to delet raw from the table
DELETE FROM mytable
WHERE condition;
- to create table
CREATE TABLE IF NOT EXISTS mytable (
    column DataType TableConstraint DEFAULT default_value,
    another_column DataType TableConstraint DEFAULT default_value,
    …
);
- to delte all the table
DROP TABLE IF EXISTS mytable;