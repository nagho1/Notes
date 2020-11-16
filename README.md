# Database Fundamentals Notes
## Data Lake - Memory Lake
* A data lake is a storage repository that holds a vast amount of raw data in its native format is needed.
* Uses flat architecture to store data
* Each element in the data lake is assigned a unique identifier 
* When a question arises, the data lake can be queried for answers
* Scalable because they lack structure

## What is a Database?
* A database is a systematic collection of data that supports electronic storage and manipulation of data.
* A database can be organized into tables, rows, columns and index it so that it is easier to find information.
* Example of a database would be a phonebook: A phone book has a list of names, phone numbers, and more information. 
* Databases can be used to handle many websites.
* Data can be stored and retrieved.

### Relational and Non-Relational Databases

### Relational Databases
 * First mentioned in 1970 paper by IBM's E.F. Codd
 * Stores data in tables and rows known as records
 * Examples: Microsoft SQL Sever, MySQL, SQLite, and PostgreSQL
 * Links data from multiple tables through the use of keys: A unique identifier that can be assigned to a row of data.
 * Primary key is used when a record has a relationship to the record in the main table
 * Foreign key is the primary key that is added to another table
 * The two keys create a relationship between the records and across multiple tables.
 * Relational Databases uses SQL(Structured Query Language) to manage data. 
 * Examples are SELECT, TO, JOIN, FROM, and WHERE
 
### Non-Relational Databases or NoSQL
 * Stores data but it does not use rows, tables, primary keys, or foreign keys.
 * They store large amounts of data with little structure
 * They provide scalability and flexibility 
 * They can capture structured, unstructured, and "BIG DATA"
 * Examples: MongoDB, Apache Cassandra, and Redis
 * Uses ORM(Object-relational mapping) to manage its data instead of SQL
 * Examples of ORMs: Java, JavaScript, .NET, and PHP


