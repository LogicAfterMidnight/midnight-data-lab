# SQL Cheat Sheet

## Start SQLite database

```
sqlite3 data/database.db
```

---

## Show tables

```
.tables
```

---

## Create table

```sql
CREATE TABLE users (
 id INTEGER PRIMARY KEY,
 name TEXT,
 age INTEGER
);
```

---

## Insert data

```sql
INSERT INTO users (name, age)
VALUES ("Alice", 25);
```

---

## Select data

```sql
SELECT * FROM users;
```

---

## Filter data

```sql
SELECT * FROM users
WHERE age > 20;
```

---

## Exit SQLite

```
.quit
```
