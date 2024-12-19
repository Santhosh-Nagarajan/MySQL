# MySQL
# Create Database
  ----------------
  create database <database_name>;

# Select Database
  ----------------
  use <database_name>;

# Create Table Simple Query
  -------------------------
  CREATE TABLE <table_name> (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(255) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL
);

# View Table List
  ---------------
  show tables;
  
# Table Data Views
  -----------------
  select * from <table_name>;

# Describe Table Query Data
  -------------
  describe <table_name>;

# Update Table Values:
  --------------------
  **example**
+----+----------+-----+
| id | username | age |
+----+----------+-----+
|  1 | Santhosh |  22 |
|  3 | sam      |  45 |
|  8 | kumar    |  33 |
+----+----------+-----+
# update cmd
update <table_name> set username='Murugan' where id=1;
**output:**
+----+----------+-----+
| id | username | age |
+----+----------+-----+
|  1 | Murugan  |  22 |
|  3 | sam      |  45 |
|  8 | kumar    |  33 |
+----+----------+-----+




