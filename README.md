# FSM

![](https://img.shields.io/bower/l/FSM?color=green) ![](https://img.shields.io/github/commit-activity/t/AmmarAbdelhalem/FSM) ![](https://img.shields.io/github/stars/AmmarAbdelhalem/FSM) ![](https://img.shields.io/github/contributors/AmmarAbdelhalem/FSM)

## What is included?


- [Introduction to databases and SQL](SQL_MAN/0-IntroductiontodatabasesandSQL.md)

- [Data Types and Data Definition](SQL_MAN/1-DataTypesandDataDefinition.md)

- [Creating and modifying database objects](SQL_MAN/2-Creatingandmodifyingdatabaseobjects.md)

- [Data manipulation](SQL_MAN/3-Datamanipulation.md)

- [Aggregate functions](SQL_MAN/4-Aggregatefunctions.md)

- [Subqueries and joins](SQL_MAN/5-Subqueriesandjoins.md)

- [Transactions and concurrency](SQL_MAN/6-Transactionsandconcurrency.md)

- [Stored procedures and triggers](SQL_MAN/7-Storedproceduresandtriggers.md)

- [Advanced topics](https://github.com/AmmarAbdelhalem/FSM/blob/main/SQL_MAN/8-Advancedtopics.md)

*If you find this useful support me with star this repo*

## Contributing

If you find any bug or you want to contribut with any information I accept that, Just create a pull request with the changes and I will check it.

## License

All assets and code are under the [MIT License](https://github.com/AmmarAbdelhalem/FSM/blob/main/LICENSE.md).


--------------------------------------------------------------------------------------------------------------------------------

## Quiz

### Quiz 1: Basic SELECT Query
**Question:**
Write a SELECT statement to fetch all columns from the `students` table.

**Answer:**
```sql
SELECT * FROM students;
```

### Quiz 2: SELECT Specific Columns
**Question:**
Write a SELECT statement to fetch only the `name` and `age` columns from the `students` table.

**Answer:**
```sql
SELECT name, age FROM students;
```

### Quiz 3: Basic INSERT Query
**Question:**
Write an INSERT statement to add a new student named 'Alice' who is 20 years old to the `students` table.

**Answer:**
```sql
INSERT INTO students (name, age) VALUES ('Alice', 20);
```

### Quiz 4: INSERT Multiple Values
**Question:**
Write an INSERT statement to add two students: 'Bob' who is 22 years old and 'Charlie' who is 23 years old to the `students` table.

**Answer:**
```sql
INSERT INTO students (name, age) VALUES ('Bob', 22), ('Charlie', 23);
```

### Quiz 5: Basic UPDATE Query
**Question:**
Write an UPDATE statement to change the age of the student named 'Alice' to 21.

**Answer:**
```sql
UPDATE students SET age = 21 WHERE name = 'Alice';
```

### Quiz 6: UPDATE Multiple Columns
**Question:**
Write an UPDATE statement to change the `age` of 'Bob' to 23 and set his `grade` to 'A'.

**Answer:**
```sql
UPDATE students SET age = 23, grade = 'A' WHERE name = 'Bob';
```

### Quiz 7: Basic DELETE Query
**Question:**
Write a DELETE statement to remove the student named 'Charlie' from the `students` table.

**Answer:**
```sql
DELETE FROM students WHERE name = 'Charlie';
```

### Quiz 8: DELETE All Records
**Question:**
Write a DELETE statement to remove all students who are older than 22 from the `students` table.

**Answer:**
```sql
DELETE FROM students WHERE age > 22;
```

### Quiz 9: SELECT with WHERE Clause
**Question:**
Write a SELECT statement to fetch all columns from the `students` table where the age is greater than 20.

**Answer:**
```sql
SELECT * FROM students WHERE age > 20;
```

### Quiz 10: SELECT with ORDER BY
**Question:**
Write a SELECT statement to fetch all columns from the `students` table and order the results by the `name` column in ascending order.

**Answer:**
```sql
SELECT * FROM students ORDER BY name ASC;
```

These quizzes are simplified to help beginners get comfortable with writing basic SQL commands.


