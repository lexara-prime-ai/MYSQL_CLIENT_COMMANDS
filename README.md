## MySQL CLI Client:

1.  **Log In to MySQL:** To log in to MySQL, open your terminal and run the following command. Replace `<username>` with your MySQL username, and you will be prompted for your password.
    
```powershell
C:> mysql -u <username> -p
```
2.  **Switch to a Database:** After logging in, you can switch to a specific database using the `USE` command.
    
```powershell
mysql> USE <database_name>;
```
3.  **Show Databases:** To list all available databases, you can use the following command:
```powershell
mysql> SHOW DATABASES;
```
4.  **Create a Database:** To create a new database, use the `CREATE DATABASE` command:
```powershell
mysql> CREATE DATABASE <database_name>;
```    
5.  **Create a Table:** To create a new table within a database, use the `CREATE TABLE` command:
```powershell 
mysql> CREATE TABLE <table_name> (
	        column1 datatype,
	        column2 datatype,
	        ...
	    );
```    
6.  **Insert Data into a Table:** You can insert data into a table using the `INSERT INTO` command:
```powershell    
mysql> INSERT INTO <table_name> (column1, column2, ...)
       VALUES (value1, value2, ...);
```
7.  **Select Data from a Table:** To retrieve data from a table, use the `SELECT` statement:
```powershell
 mysql> SELECT * FROM <table_name>;
```    
8.  **Update Data in a Table:** To update existing data in a table, use the `UPDATE` statement:
```powershell
mysql> UPDATE <table_name>
       SET column1 = value1, column2 = value2, ...
       WHERE condition;
```    
9.  **Delete Data from a Table:** To delete data from a table, use the `DELETE` statement:
```powershell    
mysql> DELETE FROM <table_name> WHERE condition;
```
10.  **Show Table Structure:** To view the structure of a table, you can use the `DESCRIBE` or `SHOW COLUMNS` command:
```powershell    
mysql> DESCRIBE <table_name>;

mysql> SHOW COLUMNS FROM <table_name>;
```    
11.  **Exit MySQL:** To exit the MySQL command-line client, you can type:
```powershell
mysql>  EXIT;
```
