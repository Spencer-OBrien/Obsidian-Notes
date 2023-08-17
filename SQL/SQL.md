### Select
```sql
SELECT * FROM table_name;
```
retrieve all the data from table_name

```sql
SELECT column_1, column2
FROM table_name;
```
retrieve column_1 and column_2 from table_name

### Delete
```sql
DELETE FROM table1;
```
delete all

```sql
DELETE FROM table1 
WHERE id = 1;
'or'
DELETE FROM table1 
WHERE name = 'Sam'
```
to delete a row from a database 

### Insert
```sql
INSERT INTO table_name (column1, column2, ...)
VALUES (value1, value2, ...);
```

### Update
```sql
UPDATE table_name
SET column1 = new_value1, column2 = new_value2, ...
WHERE condition;
```

### Alter
```sql
ALTER TABLE table_name
ADD column_name datatype;
```

### Grant
```sql
GRANT SELECT, INSERT ON table_name TO user_name;
```

### Revoke
```sql
REVOKE SELECT, INSERT ON table_name FROM user_name;
```

### Joins
```sql 
SELECT table_1.column_2, table_1.column_3, table_2.column_2
FROM table_1
JOIN table_2
ON table_1.column_1 = table_2.column_1;
```

```sql
SELECT table_1.column_2, table_1.column_3, table_2.column_2
FROM table_1
JOIN table_2
USING(column_1);
```
both of the above do the same thing joining the data in different ways
retrieve column_2 and column_3 form table_1
and column_2 form table_2 
and join the data where column_1 from table_1 is equal to column_1 from table_2

