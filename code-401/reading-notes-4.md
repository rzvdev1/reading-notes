# Data Modeling

## nosql vs sql

The best fit for the complex query intensive environment is **_SQL_** database. The best fit for hierarchical data storage is **_NoSQL_** database.
The differences in scalability between a SQl and NoSQL database are the way they are built. SQL databases are vertically scalable, NoSQL databases are horizontally scalable. SQL databases are table based, while NoSQL databases are document, key-value, graph or wide-column stores.

## sql modeling techniques

A one-to-many relationship is when a single record in one table is related to one or more records in another table, and we realte them by using a foreign key. Prior to designing your relational database, it might be useful to diagram of the database tables and their relationships.
The difference between a primary and foreign key is that a primary key is a column that has unique values for all the different rows, while a foreign key is a column that has values that correspond to the primary key in another table.

## sql vs nosql

We treat keywords and parameters differently in SQL syntax by using the keywords in the query and the parameters in the query Normalization is the process of organizing data in a database.A one-to-one relationship could be between a person and their passport. Each person can have only one passport, and each passport belongs to only one person. A one-to-many relationship could be between a customer and their orders. A customer can have multiple orders, but each order belongs to only one customer A many-to-many relationship could be between students and classes. Each student can be enrolled in multiple classes, and each class can have multiple students enrolled in it. This relationship would typically be implemented using a join table that links the two tables together.

## Reflection

My goals after reading and reviewing the class README are understanding SQL syntax, relationships within each table, and SQL Shell Commands.

### Resources I use

nosql vs sql[^1], sql modeling techniques[^2] and sql vs nosql[^3]

[^1]: [NoSQL](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
[^2]: [Modeling](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)
[^3]: [SQL](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
