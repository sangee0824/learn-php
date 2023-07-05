<a href="https://github.com/drshahizan/learn-php/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/learn-php" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/learn-php/network/members"><img src="https://img.shields.io/github/forks/drshahizan/learn-php" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/learn-php/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/learn-php" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/learn-php/issues"><img src="https://img.shields.io/github/issues/drshahizan/learn-php" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/learn-php/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/learn-php?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2Flearn-php&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

Don't forget to hit the :star: if you like this repo.

# PHP: MySQL and CRUD
## Set A
Please answer the following 50 multiple-choice questions to test your knowledge in MySQL and CRUD. You must place your answer file in the submission folder. Within the [`submission/Q5/set_a`](./submission/Q5/set_a) folder, create a folder called your `github_id`. 

1. Which of the following is a popular open-source relational database management system?
   - a) MySQL
   - b) MongoDB
   - c) Oracle
   - d) SQLite

2. How do you establish a connection to a MySQL database in PHP?
   - a) `mysqli_connect()`
   - b) `mysql_connect()`
   - c) `pdo_connect()`
   - d) `db_connect()`

3. Which PHP function is used to execute an SQL query?
   - a) `mysql_query()`
   - b) `mysqli_query()`
   - c) `pdo_query()`
   - d) `db_query()`

4. What does SQL stand for?
   - a) Structured Query Language
   - b) Sequential Query Language
   - c) Specific Query Language
   - d) Structured Question Language

5. How do you fetch a single row of data from a MySQL query result in PHP?
   - a) `mysqli_fetch_row()`
   - b) `mysqli_fetch_array()`
   - c) `mysqli_fetch_assoc()`
   - d) `mysqli_fetch_object()`

6. Which PHP function is used to retrieve the number of rows returned by a MySQL query?
   - a) `mysql_num_rows()`
   - b) `mysqli_num_rows()`
   - c) `pdo_num_rows()`
   - d) `db_num_rows()`

7. How do you escape special characters in a string before inserting it into a MySQL database?
   - a) `mysql_escape_string()`
   - b) `mysqli_escape_string()`
   - c) `pdo_escape_string()`
   - d) `db_escape_string()`

8. Which SQL statement is used to insert data into a MySQL database?
   - a) `INSERT INTO`
   - b) `UPDATE`
   - c) `SELECT`
   - d) `DELETE FROM`

9. How do you retrieve the ID of the last inserted row in a MySQL database using PHP?
   - a) `mysql_insert_id()`
   - b) `mysqli_insert_id()`
   - c) `pdo_insert_id()`
   - d) `db_insert_id()`

10. What is the result of the following PHP code?
    ```php
    $conn = mysqli_connect("localhost", "username", "password", "database");
    if (!$conn) {
        die("Connection failed: " . mysqli_connect_error());
    }
    ```
    - a) Establishes a connection to the MySQL database
    - b) Prints "Connection failed" if the connection is unsuccessful
    - c) Terminates the script execution if the connection fails
    - d) All of the above

11. Which PHP function is used to close a connection to a MySQL database?
    - a) `mysql_close()`
    - b) `mysqli_close()`
    - c) `pdo_close()`
    - d) `db_close()`

12. What does the `mysqli_fetch_array()` function return in PHP?
    - a) An associative array
    - b) A numeric array
    - c) Both associative and numeric arrays
    - d) A single value

13. How do you execute a prepared statement with placeholders in PHP using MySQLi?
    - a) `mysqli_prepare()`
    - b) `mysqli_execute()`
    - c) `mysqli_bind_param()`
    - d) `mysqli_stmt_execute()`

14. Which PHP function is used to handle errors during MySQL database operations?
    - a) `mysql_error()`
    - b) `mysqli_error()`
    - c) `pdo_error()`
    - d) `db_error()`

15. How do you retrieve the number of affected rows after an `UPDATE` or `DELETE` query in MySQLi?
    - a) `$mysqli->affected_rows`
    - b) `mysqli_affected_rows()`
    - c) `$pdo->affected_rows`
    - d) `db_affected_rows()`

16. Which PHP function is used to handle transactions in MySQL databases?
    - a) `mysql_transaction()`
    - b) `mysqli_transaction()`
    - c) `pdo_transaction()`
    - d) `db_transaction()`

17. How do you retrieve the auto-incremented ID of the last inserted row in PDO?
    - a) `$pdo->lastInsertId()`
    - b) `pdo_last_insert_id()`
    - c) `$pdo->insertId()`
    - d) `pdo_insert_id()`

18. Which SQL statement is used to update data in a MySQL database?
    - a) `UPDATE`
    - b) `INSERT INTO`
    - c) `SELECT`
    - d) `DELETE FROM`

19. How do you prevent SQL injection in PHP when working with MySQL databases?
    - a) Sanitize user input using filter functions
    - b) Use prepared statements with placeholders
    - c) Escape special characters in SQL queries
    - d) All of the above

20. What does the SQL statement `SELECT * FROM users WHERE age > 25` do?
    - a) Retrieves all users with an age greater than 25
    - b) Retrieves all users with an age less than 25
    - c) Retrieves all users from the "age" table
    - d) Retrieves all columns from the "users" table

21. How do you retrieve the number of rows returned by a PDO query?
    - a) `$pdo->rowCount()`
    - b) `pdo_num_rows()`
    - c) `count($pdo)`
    - d) `count($pdo->fetchAll())`

22. What is the result of the following code?
    ```php
    $sql = "SELECT * FROM users";
    $result = mysqli_query($conn, $sql);
    $count = mysqli_num_rows($result);
    echo $count;
    ```
    - a) Prints the number of rows in the "users" table
    - b) Prints the number of columns in the "users" table
    - c) Prints the result of the query
    - d) Error

23. Which PHP function is used to fetch the next row from a MySQL query result?
    - a) `mysql_fetch_row()`
    - b) `mysqli_fetch_row()`
    - c) `pdo_fetch_row()`
    - d) `db_fetch_row()`

24. How do you retrieve the value of a specific column from a MySQL query result in PHP?
    - a) By specifying the column name in the fetch function
    - b) By accessing the column index in the fetch function
    - c) By using the `mysql_result()` function
    - d) By using the `mysqli_result()` function

25. Which PHP function is used to free the memory associated with a MySQL query result?
    - a) `mysql_free_result()`
    - b) `mysqli_free_result()`
    - c) `pdo_free_result()`
    - d) `db_free_result()`

26. How do you retrieve the number of fields (columns) in a MySQL query result in PHP?
    - a) `$result->num_fields()`
    - b) `mysqli_num_fields($result)`
    - c) `$result->field_count()`
    - d) `count($result)`

27. Which SQL statement is used to delete data from a MySQL database?
    - a) `DELETE FROM`
    - b) `UPDATE`
    - c) `INSERT INTO`
    - d) `SELECT`

28. How do you retrieve the value of a specific field (column) from a MySQL query result in PHP?
    - a) By specifying the field name in the fetch function
    - b) By accessing the field index in the fetch function
    - c) By using the `mysql_field_result()` function
    - d) By using the `mysqli_field_result()` function

29. What is the result of the following code?
    ```php
    $sql = "SELECT COUNT(*) FROM users";
    $result = mysqli_query($conn, $sql);
    $count = mysqli_fetch_array($result)[0];
    echo $count;
    ```
    - a) Prints the number of rows in the "users" table
    - b) Prints the number of columns in the "users" table
    - c) Prints the result of the query
    - d) Error

30. How do you retrieve the error message from a failed MySQL query in PHP?
    - a) `$conn->error`
    - b) `mysqli_error()`
    - c) `$pdo->error`
    - d) `db_error()`

31. Which PHP function is used to fetch all rows from a MySQL query result at once?
    - a) `mysql_fetch_all()`
    - b) `mysqli_fetch_all()`
    - c) `pdo_fetch_all()`
    - d) `db_fetch_all()`

32. How do you retrieve the current auto-increment value for a table in MySQL using PHP?
    - a) `SHOW AUTO_INCREMENT FROM table`
    - b) `SELECT AUTO_INCREMENT FROM table`
    - c) `AUTO_INCREMENT()`
    - d) `mysql_auto_increment()`

33. Which PHP function is used to escape special characters in a string before inserting it into a MySQL database?
    - a) `mysql_escape_string()`
    - b) `mysqli_escape_string()`
    - c) `pdo_escape_string()`
    - d) `db_escape_string()`

34. How do you retrieve the number of affected rows after an `INSERT` query in MySQLi?
    - a) `$mysqli->affected_rows`
    - b) `mysqli_affected_rows()`
    - c) `$pdo->affected_rows`
    - d) `db_affected_rows()`

35. What is the result of the following code?
    ```php
    $sql = "SELECT * FROM users WHERE id = '1'";
    $result = mysqli_query($conn, $sql);
    $row = mysqli_fetch_assoc($result);
    echo $row['name'];
    ```
    - a) Prints the name of the user with ID 1
    - b) Prints the name of the first user in the table
    - c) Prints the ID of the user with name '1'
    - d) Error

36. How do you retrieve the number of rows affected by an `UPDATE` or `DELETE` query in PDO?
    - a) `$pdo->rowCount()`
    - b) `pdo_num_rows()`
    - c) `count($pdo)`
    - d) `count($pdo->fetchAll())`

37. Which PHP function is used to handle transactions in PDO?
    - a) `$pdo->transaction()`
    - b) `pdo_transaction()`
    - c) `$pdo->beginTransaction()`
    - d) `pdo_begin_transaction()`

38. How do you retrieve the auto-incremented ID of the last inserted row in MySQLi?
    - a) `$mysqli->insert_id`
    - b) `mysqli_insert_id()`
    - c) `$mysqli->lastInsertId()`
    - d) `mysqli_last_insert_id()`

39. What is the result of the following code?
    ```php
    $sql = "INSERT INTO users (name, email) VALUES ('John Doe', 'john@example.com')";
    $result = mysqli_query($conn, $sql);
    if ($result === true) {
        echo "User inserted successfully.";
    } else {
        echo "Error inserting user.";
    }
    ```
    - a) Prints "User inserted successfully" if the query is successful
    - b) Prints "Error inserting user" if the query fails
    - c) Prints nothing
    - d) Error

40. How do you retrieve the number of fields (columns) in a MySQL query result in PDO?
    - a) `$result->columnCount()`
    - b) `pdo_num_fields()`
    - c) `count($result)`
    - d) `count($result->fetch())`

41. Which PHP function is used to fetch the next row from a MySQL query result in PDO?
    - a) `$result->nextRow()`
    - b) `pdo_fetch_row()`
    - c) `$result->fetch()`
    - d) `pdo_next_row()`

42. What is the result of the following code?
    ```php
    $sql = "SELECT * FROM users";
    $result = mysqli_query($conn, $sql);
    $count = mysqli_num_fields($result);
    echo $count;
    ```
    - a) Prints the number of fields (columns) in the "users" table
    - b) Prints the number of rows in the "users" table
    - c) Prints the result of the query
    - d) Error

43. How do you retrieve the value of a specific column from a MySQL query result in PDO?
    - a) By specifying the column name in the fetch function
    - b) By accessing the column index in the fetch function
    - c) By using the `pdo_result()` function
    - d) By using the `pdo_fetch_column()` function

44. Which PHP function is used to free the memory associated with a MySQL query result in PDO?
    - a) `$result->free()`
    - b) `pdo_free_result()`
    - c) `$result->close()`
    - d) `pdo_free_memory()`

45. How do you retrieve the number of rows returned by a MySQL query in PDO?
    - a) `$result->rowCount()`
    - b) `pdo_num_rows()`
    - c) `count($result)`
    - d) `count($result->fetch())`

46. What is the result of the following code?
    ```php
    $sql = "SELECT * FROM users WHERE age > 25";
    $result = mysqli_query($conn, $sql);
    $count = mysqli_num_rows($result);
    echo $count;
    ```
    - a) Prints the number of users with an age greater than 25
    - b) Prints the number of users with an age less than 25
    - c) Prints the result of the query
    - d) Error

47. How do you retrieve the error message from a failed MySQL query in PDO?
    - a) `$pdo->errorInfo()`
    - b) `pdo_error()`
    - c) `$pdo->errorMessage()`
    - d) `pdo_error_message()`

48. Which PHP function is used to fetch all rows from a MySQL query result at once in PDO?
    - a) `$result->fetchAll()`
    - b) `pdo_fetch_all()`
    - c) `$result->getAll()`
    - d) `pdo_get_all()`

49. How do you retrieve the current auto-increment value for a table in MySQL using PHP and MySQLi?
    - a) `SHOW AUTO_INCREMENT FROM table`
    - b) `SELECT AUTO_INCREMENT FROM table`
    - c) `AUTO_INCREMENT()`
    - d) `mysqli_auto_increment()`

50. What is the result of the following code?
    ```php
    $sql = "DELETE FROM users WHERE id = 1";
    $result = mysqli_query($conn, $sql);
    if ($result) {
        echo "User deleted successfully.";
    } else {
        echo "Error deleting user.";
    }
    ```
    - a) Prints "User deleted successfully" if the query is successful
    - b) Prints "Error deleting user" if the query fails
    - c) Prints nothing
    - d) Error

## Set B
Please answer the following 50 multiple-choice questions to test your knowledge in MySQL and CRUD. You must place your answer file in the submission folder. Within the [`submission/Q5/set_b`](./submission/Q5/set_b) folder, create a folder called your `github_id`. 

1. What does CRUD stand for in the context of database operations?
    - a) Create, Read, Update, Delete
    - b) Copy, Rename, Update, Drop
    - c) Create, Remove, Upload, Delete
    - d) Control, Retrieve, Update, Destroy

2. Which PHP extension is commonly used to interact with MySQL databases?
    - a) MySQLi
    - b) PDO
    - c) SQLi
    - d) MySQLx

3. What is the purpose of the `mysqli_connect()` function in PHP?
    - a) To establish a connection to a MySQL database
    - b) To execute a SQL query
    - c) To fetch rows from a database result
    - d) To close a database connection

4. Which PHP function is used to execute a SQL query in MySQL?
    - a) `mysqli_query()`
    - b) `mysqli_fetch_assoc()`
    - c) `mysqli_connect()`
    - d) `mysqli_num_rows()`

5. What is the purpose of the `mysqli_fetch_assoc()` function in PHP?
    - a) To fetch a row from a database result as an associative array
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To get the number of rows in a database result

6. How can you retrieve the number of rows returned by a SELECT query in MySQL using PHP?
    - a) Using `mysqli_num_rows()`
    - b) Using `mysqli_query()`
    - c) Using `mysqli_fetch_assoc()`
    - d) Using `mysqli_connect()`

7. What is the purpose of the `mysqli_insert_id()` function in PHP?
    - a) To retrieve the ID generated by the previous INSERT query
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To get the number of rows affected by a query

8. Which SQL statement is used to update data in a MySQL table?
    - a) UPDATE
    - b) INSERT
    - c) SELECT
    - d) DELETE

9. Which SQL statement is used to delete data from a MySQL table?
    - a) DELETE
    - b) INSERT
    - c) UPDATE
    - d) SELECT

10. What is the purpose of the `mysqli_affected_rows()` function in PHP?
    - a) To get the number of rows affected by a query
    - b) To execute a SQL query
    - c) To fetch a row from a database result as an associative array
    - d) To establish a connection to a MySQL database

11. Which PHP function is used to escape special characters in a string to prevent SQL injection?
    - a) `mysqli_real_escape_string()`
    - b) `mysqli_query()`
    - c) `mysqli_fetch_assoc()`
    - d) `mysqli_connect()`

12. How can you retrieve the error message associated with a MySQL query in PHP?
    - a) Using `mysqli_error()`
    - b) Using `mysqli_query()`
    - c) Using `mysqli_fetch_assoc()`
    - d) Using `mysqli_connect()`

13. What is the purpose of the `mysqli_close()` function in PHP?
    - a) To close a database connection
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

14. Which PHP function is used to check if a MySQL table exists?
    - a) `mysqli_num_rows()`
    - b) `mysqli_query()`
    - c) `mysqli_fetch_assoc()`
    - d) `mysqli_table_exists()`

15. How can you retrieve the number of affected rows by an UPDATE or DELETE query in MySQL using PHP?
    - a) Using `mysqli_affected_rows()`
    - b) Using `mysqli_num_rows()`
    - c) Using `mysqli_insert_id()`
    - d) Using `mysqli_error()`

16. Which PHP function is used to handle transactions in MySQL?
    - a) `mysqli_begin_transaction()`
    - b) `mysqli_commit()`
    - c) `mysqli_rollback()`
    - d) All of the above

17. What is the purpose of the `mysqli_commit()` function in PHP?
    - a) To commit a transaction
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

18. What is the purpose of the `mysqli_rollback()` function in PHP?
    - a) To rollback a transaction
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

19. Which PHP function is used to get the last error message from a MySQL connection?
    - a) `mysqli_error()`
    - b) `mysqli_errno()`
    - c) `mysqli_connect_error()`
    - d) `mysqli_connect_errno()`

20. What is the purpose of prepared statements in PHP when working with MySQL?
    - a) To prevent SQL injection and improve performance
    - b) To execute a SQL query
    - c) To fetch rows from a database result
    - d) To establish a connection to a MySQL database

21. Which PHP function is used to bind parameters to a prepared statement in MySQL?
    - a) `mysqli_stmt_bind_param()`
    - b) `mysqli_stmt_execute()`
    - c) `mysqli_stmt_get_result()`
    - d) `mysqli_stmt_fetch()`

22. What is the purpose of the `mysqli_stmt_execute()` function in PHP when working with prepared statements?
    - a) To execute a prepared statement
    - b) To bind parameters to a prepared statement
    - c) To get the result set of a prepared statement
    - d) To fetch rows from a prepared statement result

23. What is the purpose of the `mysqli_stmt_get_result()` function in PHP when working with prepared statements?
    - a) To get the result set of a prepared statement
    - b) To execute a prepared statement
    - c) To bind parameters to a prepared statement
    - d) To fetch rows from a prepared statement result

24. How can you retrieve the rows returned by a prepared statement in PHP when working with MySQL?
    - a) Using `mysqli_stmt_get_result()`
    - b) Using `mysqli_stmt_fetch()`
    - c) Using `mysqli_stmt_execute()`
    - d) Using `mysqli_stmt_bind_param()`

25. Which PHP function is used to fetch a row from a prepared statement result in MySQL?
    - a) `mysqli_stmt_fetch()`
    - b) `mysqli_stmt_get_result()`
    - c) `mysqli_stmt_execute()`
    - d) `mysqli_stmt_bind_param()`

26. What is the purpose of the `mysqli_stmt_close()` function in PHP?
    - a) To close a prepared statement
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result
    
27. Which PHP function is used to handle errors when working with MySQL in PHP?
    - a) `mysqli_error()`
    - b) `mysqli_errno()`
    - c) `mysqli_connect_error()`
    - d) `mysqli_connect_errno()`

28. What is the purpose of the `mysqli_fetch_row()` function in PHP?
    - a) To fetch a row from a database result as an enumerated array
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To get the number of rows in a database result

29. What is the purpose of the `mysqli_fetch_array()` function in PHP?
    - a) To fetch a row from a database result as an array (both associative and enumerated)
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To get the number of rows in a database result

30. What is the purpose of the `mysqli_fetch_object()` function in PHP?
    - a) To fetch a row from a database result as an object
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To get the number of rows in a database result

31. Which PHP function is used to retrieve the number of rows returned by a SELECT query in MySQL?
    - a) `mysqli_num_rows()`
    - b) `mysqli_query()`
    - c) `mysqli_fetch_assoc()`
    - d) `mysqli_connect()`

32. What is the purpose of the `mysqli_data_seek()` function in PHP?
    - a) To move the internal result pointer to a specified row number
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

33. What is the purpose of the `mysqli_field_count()` function in PHP?
    - a) To retrieve the number of fields in a result set
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

34. Which PHP function is used to retrieve the metadata of a field in a result set in MySQL?
    - a) `mysqli_fetch_field()`
    - b) `mysqli_field_count()`
    - c) `mysqli_num_rows()`
    - d) `mysqli_data_seek()`

35. What is the purpose of the `mysqli_free_result()` function in PHP?
    - a) To free the memory associated with a result set
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

36. Which PHP function is used to retrieve the auto-generated ID of the last inserted row in MySQL?
    - a) `mysqli_insert_id()`
    - b) `mysqli_num_rows()`
    - c) `mysqli_fetch_assoc()`
    - d) `mysqli_connect()`

37. What is the purpose of the `mysqli_real_escape_string()` function in PHP when working with MySQL?
    - a) To escape special characters in a string to prevent SQL injection
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

38. How can you check if a MySQL query executed successfully in PHP?
    - a) By checking the return value of `mysqli_query()`
    - b) By checking the return value of `mysqli_fetch_assoc()`
    - c) By checking the return value of `mysqli_connect()`
    - d) By checking the return value of `mysqli_num_rows()`

39. What is the purpose of the `mysqli_num_rows()` function in PHP?
    - a) To retrieve the number of rows in a result set
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

40. Which PHP function is used to retrieve the current row of a result set in MySQL?
    - a) `mysqli_fetch_row()`
    - b) `mysqli_fetch_array()`
    - c) `mysqli_fetch_object()`
    - d) `mysqli_fetch_assoc()`

41. What is the purpose of the `mysqli_fetch_field()` function in PHP when working with MySQL?
    - a) To retrieve the metadata of a field in a result set
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

42. How can you retrieve the number of fields in a result set in PHP when working with MySQL?
    - a) Using `mysqli_field_count()`
    - b) Using `mysqli_num_rows()`
    - c) Using `mysqli_data_seek()`
    - d) Using `mysqli_fetch_field()`

43. What is the purpose of the `mysqli_fetch_all()` function in PHP?
    - a) To fetch all rows from a result set as an array
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To get the number of rows in a result set

44. Which PHP function is used to retrieve the current field value from a result set in MySQL?
    - a) `mysqli_fetch_field()`
    - b) `mysqli_fetch_row()`
    - c) `mysqli_fetch_array()`
    - d) `mysqli_fetch_assoc()`

45. What is the purpose of the `mysqli_store_result()` function in PHP?
    - a) To store the entire result set from a query in memory
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

46. How can you retrieve the number of affected rows by an INSERT, UPDATE, or DELETE query in PHP when working with MySQL?
    - a) Using `mysqli_affected_rows()`
    - b) Using `mysqli_num_rows()`
    - c) Using `mysqli_fetch_assoc()`
    - d) Using `mysqli_num_fields()`

47. What is the purpose of the `mysqli_multi_query()` function in PHP?
    - a) To execute multiple SQL queries in a single call
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

48. How can you retrieve the result of a multi-query execution in PHP when working with MySQL?
    - a) Using `mysqli_use_result()`
    - b) Using `mysqli_store_result()`
    - c) Using `mysqli_next_result()`
    - d) Using `mysqli_free_result()`

49. What is the purpose of the `mysqli_use_result()` function in PHP when working with MySQL?
    - a) To retrieve the result set of a query incrementally
    - b) To execute a SQL query
    - c) To establish a connection to a MySQL database
    - d) To fetch rows from a database result

50. Which PHP function is used to retrieve the next result from a multi-query execution in MySQL?
    - a) `mysqli_next_result()`
    - b) `mysqli_use_result()`
    - c) `mysqli_store_result()`
    - d) `mysqli_free_result()`

## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/learn-php/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)

