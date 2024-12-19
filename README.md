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
# update cmd
update <table_name> set username='Murugan' where id=1;

# Add the Row Data Insert
  -----------------------
  ## single row insert
  insert into <table_name>(username,age) values('wel',44);
   ## Insert Multiple Rows:
   insert into <table_name>(username,age) values('wel',44), ('jeep', 54);
  
# Delete Table Data
  ------------------
  delete from <table_name> where id=9;

# Table Colunm Added Alter
  -----------------------
  alter table <table_name> add column email varchar(250);
  -----
  ----

   




