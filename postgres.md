# PostgreSQL Interview Questions & Answers

### Questions

| No. | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Behavioural Questions**                                                                                                                                                                                                                   
| 1   | [What is PostgreSQL?](#What-is-postgresql)
| 2   | [What are the benefits of PostgreSQL?](#what-are-the-benefits-of-postgresql)
| 3   | [What are the main applications of PostgreSQL?](#what-are-the-main-applications-of-postgresql)
| 4   | [What are CRUD operations in PostgreSQL?](#what-are-crud-operations-in-postgresql)
| 5   | [What is a database in PostgreSQL?](#what-is-a-database-in-postgresql)
| 6   | [What is pgAdmin in PostgreSQL?](#what-is-pgadmin-in-postgresql)
| 7   | [How can you create a new database in PostgreSQL?](#how-can-you-create-a-new-database-in-postgresql)
| 8   | [How can you add new values to a certain table?](#how-can-you-add-new-values-to-a-certain-table)
| 9   | [How can you delete a database in PostgreSQL?](#how-can-you-delete-a-database-in-postgresql)
| 10  | [ What is a schema in PostgreSQL?](#what-is-a-schema-in-postgresql)
| 11  | [How can you select the five first rows in a table called ‘customers’ in PostgreSQL?](#how-can-you-select-the-five-first-rows-in-a-table-called-customers-in-postgresql)
| 12  | [What is a constraint in PostgreSQL?](#what-is-a-constraint-in-postgresql)
| 13  | [What is a join in PostgreSQL?](#what-is-a-join-in-postgresql)
| 14  | [Can you explain what is a primary key in PostgreSQL?](#can-you-explain-what-is-a-primary-key-in-postgresql)
| 15  | [Is PostgreSQL compatible with Python?](#is-postgresql-compatible-with-python)
| 16   | [What is the difference between a foreign key and a primary key in PostgreSQL?](#what-is-the-difference-between-a-foreign-key-and-a-primary-key-in-postgresql) 
| 17   | [What are the main constraints in PostgreSQL?](#what-are-the-main-constraints-in-postgresql) 
| 18   | [What is the latest version of PostgreSQL?](#what-is-the-latest-version-of-postgresql) 
| 19   | [Can you run PostgreSQL on the cloud?](#can-you-run-postgresql-on-the-cloud) 
| 20   | [What is PL/Python in PostgreSQL?](#what-is-plpython-in-postgresql) 
| 21   | [What is Multi-version Concurrency Control in PostgreSQL?](#what-is-multiversion-concurrency-control-in-postgresql) 
| 22   | [What is the maximum size for a table in PostgreSQL?](#what-is-the-maximum-size-for-a-table-in-postgresql) 
| 23   | [What are the main operators in PostgreSQL?](#what-are-the-main-operators-in-postgresql) 
| 24   | [What is an index in PostgreSQL?](#what-is-an-index-in-postgresql) 
| 25   | [What is partitioning in PostgreSQL?](#what-is-partitioning-in-postgresql) 
| 26   | [What are the 4 main properties of a transaction in PostgreSQL?](#what-are-the-4-main-properties-of-a-transaction-in-postgresql) 
| 27   | [What is Write-Ahead Logging in PostgreSQL?](#what-is-writeahead-logging-in-postgresql) 
| 28   | [What types of joins are available in PostgreSQL?](#what-types-of-joins-are-available-in-postgresql) 
| 29   | [What is a function in PostgreSQL?](#what-is-a-function-in-postgresql) 
| 30   | [What is a view in PostgreSQL?](#what-is-a-view-in-postgresql) 
| 31   | [What is normalization in PostgreSQL?](#what-is-normalization-in-postgresql)  
| 32   | [What are triggers in PostgreSQL?](#what-are-triggers-in-postgresql)  
| 33   | [How can you make a backup of a database in PostgreSQL?](#how-can-you-make-a-backup-of-a-database-in-postgresql)  
| 34   | [What is the pg_dump method used for?](#what-is-the-pg-dump-method-used-for)  
| 35   | [How can you delete a table, as well as any other object associated with it, such as views, triggers, functions, and stored procedures?](#how-can-you-delete-a-table-as-well-as-any-other-object-associated-with-it-such-as-views-triggers-functions-and-stored-procedures)  
| 36   | [What are the benefits of partitioning?](#what-are-the-benefits-of-partitioning)  
| 37   | [What is the fastest way to remove all the rows in a large table?](#what-is-the-fastest-way-to-remove-all-the-rows-in-a-large-table)  
| 38   | [What commands are used to control transactions in PostgreSQL?](#what-commands-are-used-to-control-transactions-in-postgresql)  
| 39   | [How is security ensured in PostgreSQL?](#how-is-security-ensured-in-postgresql)  
| 40   | [Imagine you have a large table with the historical daily temperature in New York. What would be the most effective strategy to partition the table?](#imagine-you-have-a-large-table-with-the-historical-daily-temperature-in-new-york-what-would-be-the-most-effective-strategy-to-partition-the-table)  
| 41   | [What is parallel querying in PostgreSQL?](#what-is-parallel-querying-in-postgresql)  
| 42   | [How can you improve query performance in PostgreSQL?](#how-can-you-improve-query-performance-in-postgresql)  
| 43   | [In which scenarios the EXPLAIN ANALYZE command can be handy?](#in-which-scenarios-the-explain-analyze-command-can-be-handy)  
| 44   | [How can you handle errors in PostgreSQL?](#how-can-you-handle-errors-in-postgresql)  
| 45   | [What is the relevance of logs for troubleshooting in PostgreSQL?](#what-is-the-relevance-of-logs-for-troubleshooting-in-postgresql)  

## Answers

1. ### What is PostgreSQL?

PostgreSQL is a lightweight, free, and open-source relational database management system. PostgreSQL is used widely across regions and companies and can be used in most popular operating systems.
  **[⬆ Back to Top](#questions)**

2. ### What are the benefits of PostgreSQL?

PostgreSQL excels among other SQL databases for several reasons, including:

- Robustness that makes it suitable for all kinds of applications,
- Free and open-source,
- Security and reliability
- Wide variety of data types,
- A big community of users worldwide.
  **[⬆ Back to Top](#questions)**

3. ### What are the main applications of PostgreSQL?

PostgreSQL allows you to:

- Create, delete, and update tables in a database,
- Access, manipulate, and modify data in a table,
- Retrieve and summarize the necessary information from a table or several tables,
- Add or remove certain rows or columns from a table
  **[⬆ Back to Top](#questions)**

4. ### What are CRUD operations in PostgreSQL?

CRUD (Create, Read, Update, Delete) operations are the basic operations in any SQL database system, including PostgreSQL. CRUD operations are frequently used in database design and management.  
  **[⬆ Back to Top](#questions)**

5. ### What is a database in PostgreSQL?

As in other SQL dialects, the database is a structured storage space where the data is kept in many tables and organized so that the necessary information can be easily fetched, manipulated, and summarized.
  **[⬆ Back to Top](#questions)**

6. ### What is pgAdmin in PostgreSQL?

pgAdmin is a handy utility that comes with the PostgreSQL installation, and it lets you do regular database-related tasks through a nice graphical interface.
  **[⬆ Back to Top](#questions)**

7. ### How can you create a new database in PostgreSQL?

PostgreSQL uses the standard CREATE DATABASE command to create new databases. But the devil is in the details. There is so much to consider when creating a database, that’s why we have prepared our <b>Creating PostgreSQL Databases Course</b> to get you covered.
  **[⬆ Back to Top](#questions)**

8. ### How can you add new values to a certain table?

PostgreSQL uses the standard INSERT INTO statement to add data to your SQL table.
  **[⬆ Back to Top](#questions)**

9. ### How can you delete a database in PostgreSQL?

To delete a database in PostgreSQL, use the DROP DATABASE command.
  **[⬆ Back to Top](#questions)**

10. ### What is a schema in PostgreSQL?

A database schema contains the logical and visual configuration of the entire relational database. In PostgreSQL, it includes the tables, along with the data types, views, indexes, sequences, constraints, and functions.
  **[⬆ Back to Top](#questions)**

11. ### How can you select the five first rows in a table called ‘customers’ in PostgreSQL?

You can retrieve that data using the following query:

SELECT * FROM customers LIMIT 5;
  **[⬆ Back to Top](#questions)**

12. ### What is a constraint in PostgreSQL?

A set of conditions defining the type of data that can be input into each column of a table. Constraints are used to ensure data integrity in a table and prevent undesired actions.
  **[⬆ Back to Top](#questions)**

13.  ### What is a join in PostgreSQL?

Joins are used to combine and retrieve records from two or multiple tables. PostgreSQL uses standard SQL joins to perform these kinds of operations.
  **[⬆ Back to Top](#questions)**

14. ### Can you explain what is a primary key in PostgreSQL?

A primary key is used to identify a row uniquely in a table. Primary keys may be made of one column or multiple columns. A primary key can be classified as a type of constraint.
  **[⬆ Back to Top](#questions)**

15.  ### Is PostgreSQL compatible with Python?

Yes, there are many packages available that allow you to use PostgreSQL through Python. Psycopg is one of the most popular Python libraries for PostgreSQL. Curious about how to use PostgreSQL through Python? Read our separate article Using PostgreSQL in Python Tutorial: Create, Connect, and Manage Databases.
  **[⬆ Back to Top](#questions)**

16. ### What is the difference between a foreign key and a primary key in PostgreSQL?

A foreign key provides shared keys between two or more tables, whereas a primary key allows only unique and strictly non-null values. Both are considered types of constraints.

**[⬆ Back to Top](#questions)**

17. ### What are the main constraints in PostgreSQL?

PostgreSQL provides the following constraints:

- Check Constraints
- Not-Null Constraints
- Unique Constraints
- Primary Keys
- Foreign Keys
- Exclusion Constraints

**[⬆ Back to Top](#questions)**

18. ### What is the latest version of PostgreSQL?

As of January 2024, the latest version is PostgreSQL 16.

**[⬆ Back to Top](#questions)**

19. ### Can you run PostgreSQL on the cloud?

Yes, PostgreSQL is compatible and can be run on most popular cloud providers, including AWS, Azure, and Google Cloud.

**[⬆ Back to Top](#questions)**

20. ### What is PL/Python in PostgreSQL?

PostgreSQL provides support to a procedural language known as PL/Python. This allows you to write SQL functions and procedures using Python.

**[⬆ Back to Top](#questions)**

21. ### What is Multi-version Concurrency Control in PostgreSQL?

Multi-version Concurrency Control (MVCC) is an advanced technique in PostgreSQL that enhances database performance in multi-user scenarios. It allows transactions to see snapshots of data as it was some time ago, protecting them from inconsistent data caused by concurrent updates.

**[⬆ Back to Top](#questions)**

22. ### What is the maximum size for a table in PostgreSQL?

While PostgreSQL provides unlimited database size, the maximum size for a table is set to 32 TB.

**[⬆ Back to Top](#questions)**

23. ### What are the main operators in PostgreSQL?

The main types of operators available in PostgreSQL are:

- Arithmetic operators
- Logical operators
- Comparison operators
- Bitwise operators

**[⬆ Back to Top](#questions)**

24. ### What is an index in PostgreSQL?

An index is a special data structure related to a table, used for storing its important parts and enabling faster data search and retrieval. Indexes significantly improve query performance, especially in large databases.

**[⬆ Back to Top](#questions)**

25. ### What is partitioning in PostgreSQL?

Partitioning is the process of splitting a large table into smaller pieces. It can be done through various methods, including range partitioning, list partitioning, and hash partitioning.

**[⬆ Back to Top](#questions)**

26. ### What are the 4 main properties of a transaction in PostgreSQL?

Transactions in PostgreSQL are expected to be Atomic, Consistent, Isolated, and Durable. These properties are commonly referred to by the acronym ACID.

**[⬆ Back to Top](#questions)**

27. ### What is Write-Ahead Logging in PostgreSQL?

Write-ahead logging is a technique used to ensure data integrity in PostgreSQL databases. It logs changes in a transaction log before modifying the database, which helps recover data in case of a crash.

**[⬆ Back to Top](#questions)**

28. ### What types of joins are available in PostgreSQL?

In PostgreSQL, the main types of joins are:

- INNER JOIN: Returns records with matching values in both tables.
- LEFT JOIN: Returns all records from the left table, and the matched records from the right table.
- RIGHT JOIN: Returns all records from the right table, and the matched records from the left table.
- FULL JOIN: Returns all records when there is a match in either the left or right table.

**[⬆ Back to Top](#questions)**

29. ### What is a function in PostgreSQL?

Functions (also known as Stored Procedures) allow you to group multiple operations into a single procedure. This procedure can be reused anytime, saving time and reducing complexity.

**[⬆ Back to Top](#questions)**

30. ### What is a view in PostgreSQL?

A view represents the result of a query on one or more underlying tables. Views simplify complex queries by defining them once and allowing repeated querying without rewriting the complex SQL.

**[⬆ Back to Top](#questions)**

31. ### What is normalization in PostgreSQL?

Database normalization is a process by which databases and tables are created or modified to address inefficiencies associated with data storage, data modification, or querying processes. In simple terms, normalization involves multiple steps to reduce data redundancy and complexity.  

**[⬆ Back to Top](#questions)**

32. ### What are triggers in PostgreSQL?

A trigger, also known as a callback function, is a specification that the database should automatically execute a particular function whenever a certain type of operation is performed. Triggers can be defined to execute either before or after any INSERT, UPDATE, or DELETE operation, either once per modified row, or once per SQL statement. If a trigger event occurs, the trigger's function is called at the appropriate time to handle the event. Triggers help ensure data integrity during the modification of a database.  

**[⬆ Back to Top](#questions)**

33. ### How can you make a backup of a database in PostgreSQL?

Making a backup of your database in PostgreSQL is fairly simple. There are various methods to perform a backup in PostgreSQL, including:

- SQL dump
- File system-level backup
- On-line backup  
- 
**[⬆ Back to Top](#questions)**

34. ### What is the pg_dump method used for?

The pg_dump method allows you to create a text file with a set of SQL commands that, when run in a PostgreSQL server, will recreate the database in the same state as it was at the moment of the dump.  

**[⬆ Back to Top](#questions)**

35. ### How can you delete a table, as well as any other object associated with it, such as views, triggers, functions, and stored procedures?

To delete a table in PostgreSQL, use the DROP TABLE command, followed by the name of the table. To ensure that any other object is associated with it, you will need to add the CASCADE command.  

**[⬆ Back to Top](#questions)**

36. ### What are the benefits of partitioning?

Partitioning allows you to divide a table into smaller, more manageable partitions, which translate into increased query performance. It’s particularly suitable when dealing with big tables.  

**[⬆ Back to Top](#questions)**

37. ### What is the fastest way to remove all the rows in a large table?

There are two main ways to remove the rows in a table: the DELETE command and the TRUNCATE command. The former is designed to remove rows more selectively and requires a full scan of the tables. The latter quickly removes all the rows and empty disk space without requiring a table scan. Therefore, the TRUNCATE command is the most suitable.  

**[⬆ Back to Top](#questions)**

38. ### What commands are used to control transactions in PostgreSQL?

There are 3 main commands to control transactions in PostgreSQL:

- BEGIN TRANSACTION or simply BEGIN: To start a transaction.
- COMMIT or END TRANSACTION: To save the changes. The COMMIT command saves all transactions to the database since the last COMMIT or ROLLBACK command.
- ROLLBACK: It’s used to undo transactions that have not already been saved to the database.  
  
**[⬆ Back to Top](#questions)**

39.  ### How is security ensured in PostgreSQL?

PostgreSQL is one of the most secure SQL databases. Security is addressed on several levels:

- Database file protection. All files stored within the database are protected from reading by any account other than the Postgres superuser account.
- Connections from a client to the database server are, by default, allowed only via a local Unix socket.
- Client connections can be restricted by IP address and/or username.
- Client connections may be authenticated via other external packages.
- Each user in Postgres is assigned a username and (optionally) a password.
- Users may be assigned to groups, and table access may be restricted based on group privileges.  
  
**[⬆ Back to Top](#questions)**

40.  ### Imagine you have a large table with the historical daily temperature in New York. What would be the most effective strategy to partition the table?

When dealing with time-series data, the most effective strategy is range partitioning, which allows the breaking of tables based on a fixed range of values. In this case, the most likely partition would be based on days.  

**[⬆ Back to Top](#questions)**

41. ### What is parallel querying in PostgreSQL?

Parallel querying is a technique in PostgreSQL that allows you to create query plans that can leverage multiple CPUs to answer queries more efficiently. This technique is particularly well-suited when the query involves scanning a lot of data but returning a few rows, for example, aggregate calculations.  

**[⬆ Back to Top](#questions)**

42. ### How can you improve query performance in PostgreSQL?

There are multiple strategies to increase query performance, including:

- Using indexing, especially in queries that involve WHERE clauses;
- Writing efficient SQL statements to reduce processing overhead, for example, by avoiding unnecessary columns in the SELECT statement.
- Implementing partitioning for large tables.
- Optimizing memory usage by tuning server parameters to match hardware specifications.  
Especially when dealing with large databases, improving your query performance is crucial to avoid undesired bottlenecks.  

**[⬆ Back to Top](#questions)**

43. ### In which scenarios the EXPLAIN ANALYZE command can be handy?

The EXPLAIN command shows you the execution plan of a SQL statement. This includes the manner the table(s) referenced in your statement will be processed, the underlying algorithms that will be used for complex operations, such as joins, as well as the estimated execution time.

If, in addition to the estimated time, you want to know the actual time required, you can add the ANALYZE command, and the statement will be actually executed, not only planned.

Overall, The EXPLAIN ANALYZE command is particularly handy to spot bottleneck in complex queries so you can rewrite them to improve query performance.  

**[⬆ Back to Top](#questions)**

44. ### How can you handle errors in PostgreSQL?

There are two main ways to address errors in PostgreSQL:

- Callback functions can be developed to handle warning and error conditions. In this case, you can specify a certain behavior in case of errors and warnings in your queries using the WHENEVER command.
- Detailed information about the error or warning can be obtained from the sqlca variable. This variable provides detailed information when errors and warnings arise during execution.  
  
**[⬆ Back to Top](#questions)**

45.  ### What is the relevance of logs for troubleshooting in PostgreSQL?

PostgreSQL logs are a valuable resource for troubleshooting problems, tracking performance, and auditing database activity. PostgreSQL comes with a wide variety of logs, including error logs. These logs can help you spot queries and statements that lead to errors during execution.  

**[⬆ Back to Top](#questions)**