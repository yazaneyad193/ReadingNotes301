# Read:08 \| SQL


## Notes from [SQL Bolt Lessons](http://sqlbolt.com/)

#### Retrieving data

- To retrieve data form a SQL database, use `SELECT` statements
- A "table" in SQL is a type of entity, while each row is an instance of that type
- Columns are properties shared by all instances (rows) of the entity (table)
- A simple select statement:

  ```sql
  SELECT column, another_column
  FROM mytable;
  ```
- The `*` shorthand means "all columns" and can be used in SELECT: `SELECT * FROM mytable`
- A`WHERE` clause takes a condition to find a specific set of rows
- Here are some operators that can be used with `WHERE`:

  
  
  #### Modifying data

- A "schema" describes the structure of the table and data types of each column. For example, the year column should be an integer and the title should be a string.
- `INSERT` query puts rows into the table into the specified columns. Here is an example:

  

- `VALUES` for the INSERT are listed in parentheses.
- `UPDATE` queries update rows in the database.

  > Note: Always use a `SELECT` query to make sure you are updating the right rows before updating.

 
