# Journal Day 4 - Week 4

## Daily Journal Questions

1. In a SQL table, what is the difference between information in a row and information in a column?

    The information in a row will contain all of the values for a specific item in a list, where as a column is going to contain all of the values of a specific key for every single item in a list.

2. Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

    CREATE TABLE characters
    (
        name VARCHAR(255) NOT NULL,
        age VARCHAR(255) NOT NULL,
        description VARCHAR(255) NOT NULL,
        id int AUTO_INCREMENT
    )

3. What is the difference between the following statements:
        DELETE FROM table_name;
        DROP TABLE table_name;

    DELETE FROM will delete a single item from the table. DROP TABLE will delete the WHOLE table, and all of the data inside of it.


