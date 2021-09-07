# CONNECTING TO A MYSQL DATABASE


## In a SQL table, what is the difference between information in a row and information in a column?
Row is an entry.
Columns are the attributes.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE characters(
    id int NOT NULL primary key AUTO_INCREMENT comment 'primary key',
    name varchar(255) comment 'character name',
    age int comment 'character age',
    description varchar(255) comment 'character description'
);

## What is the difference between the following statements:
## DELETE FROM table_name;
## DROP TABLE table_name;
Delete From removes an entry from a table.
Drop Table removes the entire existence of the table

# Afternoon Challenge:
https://github.com/LucWeidell/knightsTale