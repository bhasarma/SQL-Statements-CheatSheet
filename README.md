# SQL Statements Explained: From Basics to Advanced

This repo provides a comprehensive collection of SQL statements, along with clear explanations and examples, to help learners understand and master 
SQL for querying and managing databases.

| S. No. |Statements|Explanation|
| ------ | -------- | ----------|
| 1. | SHOW DATABASES;| Displays a list of all available databases |
| 2. | CREATE DATABASE <database_name>; | Creates a new (empty) databse  |
| 3. | DROP DATABASE <database_name>; | Deletes an existing database |
| 4. | USE <database_name>; | Brings the user inside the database |
| 5. | SELECT database(); | Returns the name of currently selected database |

6. Creating a table:
   
    ```
    CREATE TABLE <table_name> (    
        column_name_1 datatype_1,    
        column_name_2 datatype_2
    );
    ```

| S. No. |Statements|Explanation|
| ------ | -------- | ----------|
| 7. | SHOW TABLES; | Displays tables inside the current database |
| 8. | SHOW COLUMNS FROM <table_name>;| Displays name of columns in the table |
| 9. | DESC <table_name>;| Describes the table |
| 10. | DESCRIBE <table_name>;| Describes the table |
| 11. | DROP TABLE <table_name>; | Deletes the table from the database |