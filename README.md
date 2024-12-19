# MySQL
# Create Database
  ----------------
  create database <database_name>

# Select Database
  ----------------
  use <database_name>

# Create Table Simple Query
  CREATE TABLE <table_name> (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(255) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL
);
