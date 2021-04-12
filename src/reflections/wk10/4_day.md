## Day 4

### Database Structure & Syntax

#### 1. In a SQL table, what is the difference between information in a row and information in a column?

```Column info will always be of the same type. Rows will be all one object with different properties.```

#### 2. Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

```sql
CREATE TABLE characters (
    charName varchar(255),
    age varchar(3),
    charDesc varchar(255),
    id int
);
```

#### 3. What is the difference between the following statements:
```sql
DELETE FROM table_name;
DROP TABLE table_name;
```
```The first will delete all items in the table, the second will delete the whole table.```
