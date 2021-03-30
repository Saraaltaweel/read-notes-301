## SQL
## What is SQL?

* SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.

## Relational databases
- represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.

- To retrieve data from a SQL database, we need to write SELECT statements, which are often colloquially refered to as queries.

- A query in itself is just a statement which declares what data we are looking for, where to find it in the database, and optionally, how to transform it before it is returned.

- The result of a query will be a two-dimensional set of rows and columns, effectively a copy of the table, but only with the columns that we requested.

- If we want to retrieve absolutely all the columns of data from a table, we can then use the asterisk (*) shorthand in place of listing all the column names individually.

- In order to filter certain results from being returned, we need to use a WHERE clause in the query.

## What is a Schema?
- the database schema is what describes the structure of each table, and the datatypes that each column of the table can contain.

- When inserting data into a database, we need to use an INSERT statement, which declares which table to write into, the columns of data that we are filling, and one or more rows of data to insert.

- In addition to adding new data, a common task is to update existing data, which can be done using an UPDATE statement.

- When you need to delete data from a table in the database, you can use a DELETE statement, which describes the table to act on, and the rows of the table to delete through the WHERE clause.

- you can create a new database table using the CREATE TABLE statement.