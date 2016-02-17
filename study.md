# Structure Query Language Study

Please _read_ the following in the
[PostgreSQL Documentation](http://www.postgresql.org/docs/9.5/static/index.html):
the [Preface](http://www.postgresql.org/docs/9.5/static/preface.html) excluding
[Bug Reporting Guidelines](http://www.postgresql.org/docs/9.5/static/bug-reporting.html);
Part I. [Tutorial](http://www.postgresql.org/docs/9.5/static/tutorial.html),
Chapter 1. [Getting Started](http://www.postgresql.org/docs/9.5/static/tutorial-start.html)
and Chapter 2. [The SQL Language](http://www.postgresql.org/docs/9.5/static/tutorial-sql.html).
You are not expected to create tutorial files as described in [2.1. Introduction](http://www.postgresql.org/docs/9.5/static/tutorial-sql-intro.html).

## Notations conventions

What characters denote optional parts of a command?
Show the characters and give their name.

```md
[] - brackets denote optional parts
```

What characters indicate a possibly repeating element in a command?
Show the characters and give their name.

```md
... - dots indicate repeating element
```

## Creating or removing a database

What shell command would you execute to create a database named `mydb`?

```sh
createdb mydb;
```

What shell command would you execute to remove a database named `mydb`?

```sh
DROP DATABASE [ IF EXISTS ] mydb
```

## Creating or removing a table

What two SQL keywords precede the table name when creating a database table?

```sql
CREATE TABLE new_table_name
```

What is the SQL command to remove a database table named `mytable`?

```sql
DROP TABLE [ IF EXISTS ] mytable
```

## Table row CRUD

What two SQL keywords precede the table name when populating
a database table with rows?

```sql
INSERT INTO table_name
```

What SQL keyword starts the command to retrieve data from a database table?

```sql
SELECT column_name,column_name
FROM table_name;
```

What SQL command is used to update existing rows in a database table?

```sql
UPDATE table_name
SET column1=value1,column2=value2,...
WHERE some_column=some_value;
```

What SQL command is used to remove rows from a database table?

```sql
DELETE FROM table WHERE id = 1;
```
