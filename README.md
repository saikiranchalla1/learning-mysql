# MySQL
## What is MySQL
You deal with data every day…

When you want to listen to your favorite songs, you open your playlist from your smartphone. In this case, the playlist is a database.

When you take a photo and upload it to your account on a social network like Facebook, your photo gallery is a database.

When you browse an e-commerce website to buy shoes, clothes, etc., you use the shopping cart database.

Databases are everywhere. So what is a database?  By definition, a database is merely a structured collection of data.

The data relating to each other by nature, e.g., a product belonged to a product category and associated with multiple tags. Therefore, we use the term relational database.

In the relational database, we model data like products, categories, tags, etc., using tables. A table contains columns and rows. It is like a spreadsheet.

A table may relate to another table using a relationship, e.g., one-to-one and one-to-many relationships.

Because we deal with a significant amount of data, we need a way to define the databases, tables, etc., and process data more efficiently. Besides, we want to turn the data into information.

And this is where SQL comes to play.

### SQL – the language of the relational database
SQL stands for the structured query language.

SQL is the standardized language used to access the database.

ANSI/SQL defines the SQL standard. The current version of SQL is SQL:2016. Whenever we refer to the SQL standard, we mean the current SQL version.

SQL contains three parts:

- Data definition language includes statements that help you define the database and its objects, e.g., tables, views, triggers, stored procedures, etc.
- Data manipulation language contains statements that allow you to update and query data.
- Data control language allows you to grant the permissions to a user to access specific data in the database.
- Now, you understand database and SQL, and it’s time to answer the next question…
  
### What is MySQL
MySQL? What?

My is the daughter’s name of the MySQL’s co-founder, Monty Widenius.

The name of MySQL is the combination of My and SQL, MySQL.

MySQL is a database management system that allows you to manage relational databases. It is open source software backed by Oracle. It means you can use MySQL without paying a dime. Also, if you want, you can change its source code to suit your needs.

Even though MySQL is open source software, you can buy a commercial license version from Oracle to get premium support services.

MySQL is pretty easy to master in comparison with other database software like Oracle Database, or Microsoft SQL Server.

MySQL can run on various platforms UNIX, Linux, Windows, etc. You can install it on a server or even in a desktop. Besides, MySQL is reliable, scalable, and fast.

The official way to pronounce MySQL is My Ess Que Ell, not My Sequel. However, you can pronounce it whatever you like, who cares?

If you develop websites or web applications, MySQL is a good choice. MySQL is an essential component of the LAMP stack, which includes Linux, Apache, MySQL, and PHP.

## Install MySQL
### Windows:

Step 1: Download MySQL Installer:

Visit the MySQL Community Downloads page (https://dev.mysql.com/downloads/) in your web browser.
Scroll down to the MySQL Community (GPL) Downloads section.
Click on the "MySQL Installer" link to download the installer.
Step 2: Run the Installer:

Locate the downloaded installer file and double-click on it to run it.
If prompted for User Account Control (UAC), click "Yes" to allow the installer to make changes to your system.
Step 3: Choose Setup Type:

The installer will launch and present you with setup options. Choose the "Developer Default" setup type, which includes the MySQL Server, Workbench, and other useful tools.
Click "Next" to proceed.
Step 4: Check Requirements:

The installer will check if your system meets the necessary requirements for installation. If any requirements are missing, the installer will prompt you to install them.
Click "Next" once the requirements check passes.
Step 5: Select Products:

On the product selection screen, ensure that "MySQL Server" and "MySQL Workbench" are selected.
You can also select additional tools or connectors based on your needs.
Click "Next" to continue.
Step 6: Choose Installation Type:

Select the "Standalone MySQL Server / Classic MySQL Replication" option.
Click "Next" to proceed.
Step 7: Configure MySQL Server:

Choose a username and password for the MySQL root account. Make sure to remember these credentials as you'll need them later.
You can also configure additional options such as port number, service name, and authentication method.
Click "Next" once you've configured the options.
Step 8: Perform Installation:

The installer will display a summary of the installation configuration. Review the settings and click "Execute" to start the installation process.
Wait for the installer to download and install the selected components.
Step 9: Complete the Installation:

Once the installation completes, the installer will display a screen with installation details.
Click "Next" and then "Finish" to exit the installer.
That's it! MySQL is now installed on your Windows machine.

### macOS:

Step 1: Download MySQL DMG Package:

Visit the MySQL Community Downloads page (https://dev.mysql.com/downloads/) in your web browser.
Scroll down to the MySQL Community (GPL) Downloads section.
Click on the "macOS (x86, 64-bit), DMG Archive" link to download the DMG package.
Step 2: Open the DMG Package:

Locate the downloaded DMG package in your Downloads folder.
Double-click on the DMG file to open it.
A new Finder window will open containing the MySQL installer package.
Step 3: Run the Installer:

Double-click on the MySQL installer package (.pkg file) to launch the installer.
If prompted, click "Continue" on the Introduction screen.
Step 4: Choose Installation Type:

On the Installation Type screen, choose the "Install MySQL for Excel" option.
Click "Continue" to proceed.
Step 5: Agree to the License Terms:

Read the license agreement, and if you agree, click "Continue."
Click "Agree" to accept the terms and proceed.
Step 6: Select Installation Location:

By default, the installer will suggest the installation location. You can change it if desired.
Click "Install" to begin the installation process.
Step 7: Provide Administrator Password:

The installer may prompt you to enter your macOS administrator password. Provide the password and click "Install Software" to continue.
Step 8: Complete the Installation:

Wait for the installer to copy the necessary files and complete the installation.
Once the installation finishes, click "Close" to exit the installer.
That's it! MySQL is now installed on your macOS machine.

After the installation, you can start the MySQL server and connect to it using MySQL Workbench or the MySQL Command Line Client.

## Connect to MySQL Server
Here are detailed instructions on how to connect to MySQL using the MySQL Command Line Client:

Step 1: Open the Command Line (Terminal or Command Prompt):

On Windows: Press the Windows key, type "Command Prompt," and open it.
On macOS: Press Command + Space, type "Terminal," and open it.
Step 2: Launch the MySQL Command Line Client:

Type the following command and press Enter:

```
mysql -u username -p
```


Replace "username" with the MySQL username you want to use for the connection.
Step 3: Enter the MySQL Password:

After pressing Enter, the command will prompt you to enter the password for the MySQL user.
Type the password and press Enter. Note that the password characters will not be visible on the screen for security reasons.
Step 4: Verify the Connection:

If the credentials are correct, the MySQL Command Line Client will establish a connection to the MySQL server.
You will see a welcome message and the MySQL command prompt, which looks like:

```
mysql>
```

Step 5: Perform Database Operations:

Now that you are connected to MySQL, you can perform various database operations using SQL commands.
For example, you can create databases, create tables, insert data, retrieve data, and modify data using appropriate SQL statements.
Step 6: Exit the MySQL Command Line Client:

To exit the MySQL Command Line Client, type the following command and press Enter:

```
exit
```

That's it! You have successfully connected to MySQL using the MySQL Command Line Client

## MySQL Sample Database
Here are detailed instructions on how to use the MySQL sample database:

Step 1: Download the Sample Database:

Visit the MySQL Documentation page (https://dev.mysql.com/doc/index-other.html).
Scroll down to the "Example Databases" section.
Look for the sample database named "Sakila Database."
Click on the "sakila-db.zip" link to download the sample database ZIP file.
Step 2: Extract the Sample Database:

Locate the downloaded ZIP file and extract its contents to a directory of your choice.
You should have a folder named "sakila-db" containing the sample database files.
Step 3: Connect to MySQL Server:

Open the MySQL Command Line Client or a MySQL GUI tool like MySQL Workbench.
Connect to the MySQL server using your preferred method. For example, if using the MySQL Command Line Client, use the following command:

```
mysql -u username -p
```

Replace "username" with your MySQL username.

Step 4: Create the Sakila Database:

If the "sakila" database does not exist, you need to create it. Use the following command:

```
CREATE DATABASE sakila;
```

Step 5: Load the Sample Database:

Now, you need to load the sample database into the newly created "sakila" database. Use the following command:

```
USE sakila;
SOURCE /path/to/sakila-db/sakila-schema.sql;
SOURCE /path/to/sakila-db/sakila-data.sql;
```

Replace "/path/to/sakila-db" with the actual path to the "sakila-db" folder on your system.
Step 6: Verify the Sample Database:

Once the commands complete successfully, the Sakila sample database should be loaded into the "sakila" database.
You can verify this by running queries against the Sakila database tables.
For example, you can try the following query to retrieve information about films in the database:

```
USE sakila;
SELECT * FROM film;
```

That's it! You have successfully loaded and can now use the Sakila sample database in MySQL.

The Sakila sample database provides a realistic schema and data for a DVD rental store, allowing you to practice SQL queries and explore database operations. You can refer to the Sakila documentation (https://dev.mysql.com/doc/sakila/en/) for more information about the database structure and sample queries.

Note: The file paths and commands mentioned in the instructions may vary depending on your operating system and MySQL installation. Please adjust them accordingly.


## MySQL Select
1. Basic SELECT:
To retrieve data from a table in the Sakila database, you can use the SELECT statement. Let's start with a basic example to select all rows from the actor table:

```
USE sakila;
SELECT * FROM actor;
```

This query selects all columns (*) from the actor table.

1. Specifying Columns:
Instead of selecting all columns, you can specify specific columns to retrieve. Here's an example to select only the first_name and last_name columns from the actor table:

```
SELECT first_name, last_name FROM actor;
```

This query will return only the first_name and last_name columns for all rows in the actor table.

1. Aliasing Columns:
You can provide custom names to columns using aliases. Aliases are useful for renaming columns or making the output more readable. Here's an example to select the first_name column aliased as "First Name" and the last_name column aliased as "Last Name":

```
SELECT first_name AS "First Name", last_name AS "Last Name" FROM actor;
```

The result will display the column names as "First Name" and "Last Name" instead of the original column names.

1. Filtering Rows with WHERE:
To filter rows based on specific conditions, you can use the WHERE clause. Here's an example to select actors with the first name "Tom":

```
SELECT * FROM actor WHERE first_name = 'Tom';
```

This query retrieves all columns for actors whose first_name is equal to 'Tom'.

You can use various operators (=, <>, >, <, >=, <=, LIKE, etc.) in the WHERE clause to compare values.

1. Sorting Rows with ORDER BY:
To sort the result set based on specific columns, you can use the ORDER BY clause. Here's an example to select actors and order them by their last name in ascending order:

```
SELECT * FROM actor ORDER BY last_name ASC;
```

You can use ASC for ascending order or DESC for descending order.

1. Limiting the Result Set with LIMIT:
To retrieve a specific number of rows from the result set, you can use the LIMIT clause. Here's an example to select the first five actors from the actor table:

```
SELECT * FROM actor LIMIT 5;
```

This query returns only the first five rows from the actor table.

These are some of the essential aspects of using the SELECT statement in MySQL with the Sakila sample database. Remember to adjust the table and column names based on your specific needs.

## MySQL WHERE
1. Ascending Order:
By default, the ORDER BY clause sorts the result set in ascending order. Let's start with a basic example to retrieve all films from the film table and order them by their title in ascending order:

```
USE sakila;
SELECT * FROM film ORDER BY title;
```

This query will return all films from the film table, sorted in ascending order based on the title column.

1. Descending Order:
To sort the result set in descending order, you can use the DESC keyword after the column name in the ORDER BY clause. Here's an example to retrieve all films and order them by their length in descending order:

```
SELECT * FROM film ORDER BY length DESC;
```

This query will return all films, sorted in descending order based on the length column.

1. Sorting Multiple Columns:
You can also sort the result set based on multiple columns. When multiple columns are specified in the ORDER BY clause, the sorting occurs first by the first column, then by the second column if there are ties, and so on. Here's an example to retrieve all films and order them by release_year in descending order and then by rating in ascending order:

```
SELECT * FROM film ORDER BY release_year DESC, rating ASC;
```

This query will return all films, first sorted in descending order by release_year, and then within each release_year value, sorted in ascending order by rating.

1. Sorting by Column Position:
Instead of specifying the column name in the ORDER BY clause, you can also use the column position (starting from 1) to sort the result set. This can be helpful when you don't want to repeat the column name. Here's an example to retrieve all actors and order them by the second column (last_name) in ascending order:

```
SELECT * FROM actor ORDER BY 2 ASC;
```

This query will return all actors, sorted in ascending order by the second column (last_name).

1. Sorting NULL Values:
By default, NULL values are sorted at the end of the result set in ascending order and at the beginning in descending order. If you want to change this behavior, you can use the NULLS FIRST or NULLS LAST keywords in the ORDER BY clause. Here's an example to retrieve all customers and order them by their last_update column, with NULL values appearing first:

```
SELECT * FROM customer ORDER BY last_update NULLS FIRST;
```

This query will return all customers, sorted based on their last_update column, with NULL values appearing first.

These are some of the important aspects of using the ORDER BY clause in MySQL with the Sakila sample database.

## MySQL DISTINCT
1. Basic Usage:
The DISTINCT clause is used to retrieve unique values from a column in a table. Let's start with a basic example to retrieve all unique values from the category column in the film table:

```
USE sakila;
SELECT DISTINCT category FROM film;
```

This query will return all distinct values from the category column in the film table.

1. Multiple Columns:
You can also use the DISTINCT clause with multiple columns to retrieve unique combinations of values. Here's an example to retrieve all unique combinations of first_name and last_name columns from the actor table:

```
SELECT DISTINCT first_name, last_name FROM actor;
```

This query will return all distinct combinations of first_name and last_name from the actor table.

1. Using DISTINCT with COUNT:
You can combine the DISTINCT clause with the COUNT function to count the number of unique values in a column. Here's an example to count the number of unique category values in the film table:

```
SELECT COUNT(DISTINCT category) AS unique_categories FROM film;
```

This query will return the count of unique category values in the film table, aliased as unique_categories.

1. Distinct with Multiple Columns and Count:
You can also use the DISTINCT clause with multiple columns within the COUNT function. Here's an example to count the number of unique combinations of first_name and last_name in the actor table:

```
SELECT COUNT(DISTINCT first_name, last_name) AS unique_actors FROM actor;
```

This query will return the count of unique combinations of first_name and last_name in the actor table, aliased as unique_actors.

1. Limitations of DISTINCT:
It's important to note that the DISTINCT clause operates on the entire row, not just a single column. It will consider the combination of values across all selected columns. If you want to retrieve distinct values from only one column, make sure to include only that column in the SELECT statement.

## MySQL AND, OR, In, BETWEEN, LIMIT, IS NULL, LIKE
1. AND Operator:
The AND operator is used to combine multiple conditions in a WHERE clause. It returns true if all the conditions are met. Here's an example to retrieve films from the film table where the rating is 'PG-13' and the length is greater than 120 minutes:

```
USE sakila;
SELECT * FROM film WHERE rating = 'PG-13' AND length > 120;
```

This query will return films that satisfy both conditions.

1. OR Operator:
The OR operator is used to combine multiple conditions in a WHERE clause. It returns true if at least one of the conditions is met. Here's an example to retrieve films from the film table where the rating is 'PG-13' or the rating is 'R':

```
SELECT * FROM film WHERE rating = 'PG-13' OR rating = 'R';
```

This query will return films that have either 'PG-13' or 'R' as the rating.

1. IN Operator:
The IN operator is used to specify multiple values in a WHERE clause. It allows you to match a column against a list of specified values. Here's an example to retrieve films from the film table where the rating is either 'PG-13', 'R', or 'G':

```
SELECT * FROM film WHERE rating IN ('PG-13', 'R', 'G');
```

This query will return films that have the rating 'PG-13', 'R', or 'G'.

1. BETWEEN Operator:
The BETWEEN operator is used to select values within a specified range. Here's an example to retrieve films from the film table where the length is between 90 and 120 minutes:

```
SELECT * FROM film WHERE length BETWEEN 90 AND 120;
```

This query will return films that have a length between 90 and 120 minutes (inclusive).

1. LIKE Operator:
The LIKE operator is used to perform pattern matching in a WHERE clause. It is often used with wildcard characters (% and _). Here's an example to retrieve films from the film table where the title starts with 'A' and ends with 'e':

```
SELECT * FROM film WHERE title LIKE 'A%e';
```

This query will return films with titles that start with 'A' and end with 'e'.

1. LIMIT Operator:
The LIMIT clause is used to limit the number of rows returned by a query. Here's an example to retrieve the first five films from the film table:

```
SELECT * FROM film LIMIT 5;
```

This query will return only the first five rows from the film table.

1. IS NULL Operator:
The IS NULL operator is used to check if a column has a NULL value. Here's an example to retrieve films from the film table where the description column is NULL:

```
SELECT * FROM film WHERE description IS NULL;
```

This query will return films that have a NULL value in the description column.

These are some of the commonly used operators in MySQL to perform logical operations, value matching, range selection, and result limiting. 

## MySQL JOINS
1. Introduction to Joins:
In MySQL, joins are used to combine rows from two or more tables based on related columns between them. Joins allow you to retrieve data from multiple tables in a single query. The most commonly used types of joins are INNER JOIN, LEFT JOIN, and RIGHT JOIN.

2. INNER JOIN:
The INNER JOIN returns only the rows that have matching values in both tables. Here's an example to retrieve the film title and the corresponding category name from the film and category tables:

```
USE sakila;
SELECT film.title, category.name
FROM film
INNER JOIN film_category ON film.film_id = film_category.film_id
INNER JOIN category ON film_category.category_id = category.category_id;
```

In this query, the INNER JOIN is used to match rows between the film and film_category tables based on the film_id column, and then between the film_category and category tables based on the category_id column. The result will contain the film title and the corresponding category name.

1. LEFT JOIN:
The LEFT JOIN returns all rows from the left table and the matching rows from the right table. If there are no matching rows in the right table, NULL values are included. Here's an example to retrieve the customer's first name and the corresponding rental information from the customer and rental tables:

```
SELECT customer.first_name, rental.rental_date
FROM customer
LEFT JOIN rental ON customer.customer_id = rental.customer_id;
```

In this query, the LEFT JOIN is used to match rows between the customer and rental tables based on the customer_id column. The result will contain the customer's first name and the corresponding rental date. If a customer has no rental information, NULL values will be included for the rental date.

1. RIGHT JOIN:
The RIGHT JOIN returns all rows from the right table and the matching rows from the left table. If there are no matching rows in the left table, NULL values are included. Here's an example to retrieve the payment ID and the corresponding customer's email address from the payment and customer tables:

```
SELECT payment.payment_id, customer.email
FROM payment
RIGHT JOIN customer ON payment.customer_id = customer.customer_id;
```

In this query, the RIGHT JOIN is used to match rows between the payment and customer tables based on the customer_id column. The result will contain the payment ID and the corresponding customer's email address. If a payment has no corresponding customer, NULL values will be included for the email address.

1. Self-Join:
A self-join is a join where a table is joined with itself. It can be useful when you want to compare rows within the same table. Here's an example to retrieve the customer's first name and the name of the customer who referred them:

```
SELECT c1.first_name, c2.first_name AS referred_by
FROM customer c1
LEFT JOIN customer c2 ON c1.referred_by = c2.customer_id;
```

In this query, the customer table is joined with itself using a LEFT JOIN based on the referred_by and customer_id columns. The result will contain the customer's first name and the name of the customer who referred them. If a customer does not have a referrer, NULL values will be included for the referred_by column.

These are some of the commonly used join types in MySQL. Feel free to explore more advanced topics, such as FULL JOIN or using aliases, as you become more comfortable. The official MySQL documentation (https://dev.mysql.com/doc/) is a valuable resource for further learning and reference.

## MySQL DML
1. INSERT Statement:
The INSERT statement is used to add new rows to a table. Here's an example to insert a new film into the film table:

```
USE sakila;
INSERT INTO film (title, description, release_year, language_id)
VALUES ('My New Film', 'This is a great film', 2023, 1);
```

This query will insert a new film with the specified values into the film table.

1. INSERT Multiple Rows:
You can also insert multiple rows into a table with a single INSERT statement. Here's an example to insert multiple films into the film table:

```
INSERT INTO film (title, description, release_year, language_id)
VALUES ('Film 1', 'Description 1', 2023, 1),
       ('Film 2', 'Description 2', 2023, 1),
       ('Film 3', 'Description 3', 2023, 1);
```

This query will insert three new films with the specified values into the film table.

1. INSERT INTO SELECT Statement:
The INSERT INTO SELECT statement allows you to insert data from one table into another. Here's an example to insert films from the film table into a new table film_copy:

```
CREATE TABLE film_copy AS
SELECT * FROM film;
```

This query will create a new table film_copy with the same structure as the film table and insert all the films into it.

1. INSERT IGNORE Statement:
The INSERT IGNORE statement is used to insert new rows into a table, but it ignores any duplicate key errors. Here's an example to insert a new film into the film table, ignoring any duplicate entries:

```
INSERT IGNORE INTO film (title, description, release_year, language_id)
VALUES ('My New Film', 'This is a great film', 2023, 1);
```

If there is a duplicate key violation, the INSERT IGNORE statement will not generate an error, and the insertion will be ignored.

1. UPDATE Statement:
The UPDATE statement is used to modify existing data in a table. Here's an example to update the rental duration of a film in the film table:

```
UPDATE film SET rental_duration = 7 WHERE film_id = 1;
```

This query will update the rental_duration column of the film with film_id = 1 to 7.

1. DELETE Statement:
The DELETE statement is used to remove rows from a table. Here's an example to delete a film from the film table:

```
DELETE FROM film WHERE film_id = 1;
```

This query will delete the film with film_id = 1 from the film table.

1. ON DELETE CASCADE:
The ON DELETE CASCADE is a referential action that allows you to automatically delete related rows in other tables when a row is deleted from a parent table. Here's an example to add the ON DELETE CASCADE constraint to the customer table:

```
ALTER TABLE customer
ADD FOREIGN KEY (store_id)
REFERENCES store(store_id)
ON DELETE CASCADE;
```

This query will add the ON DELETE CASCADE constraint to the store_id column in the customer table. When a row is deleted from the store table, all related rows in the customer table with the corresponding store_id will be deleted as well.

1. REPLACE Statement:
The REPLACE statement is used to insert a new row into a table, or if a duplicate key exists, it will delete the existing row and insert a new one. Here's an example to replace a film in the film table:

```
REPLACE INTO film (film_id, title, description, release_year, language_id)
VALUES (1, 'Updated Film', 'This is an updated film', 2023, 1);
```

If a film with film_id = 1 exists, it will be replaced with the new values specified in the REPLACE statement. If it doesn't exist, a new row will be inserted.

These are some of the commonly used data manipulation statements in MySQL.

## MySQL Constraints
1. Primary Key Constraint:
A primary key constraint is used to uniquely identify each row in a table. It ensures that the primary key column(s) have unique and non-null values. Here's an example of adding a primary key constraint to the actor table:

```
USE sakila;
ALTER TABLE actor
ADD PRIMARY KEY (actor_id);
```

In this query, the actor_id column is designated as the primary key for the actor table. It guarantees that each actor has a unique identifier.

1. Foreign Key Constraint:
A foreign key constraint is used to establish a relationship between two tables based on a column's values. It ensures referential integrity by enforcing that values in the foreign key column(s) exist in the referenced table's primary key column(s). Here's an example of adding a foreign key constraint to the film table, referencing the language table:

```
ALTER TABLE film
ADD CONSTRAINT fk_film_language
FOREIGN KEY (language_id)
REFERENCES language (language_id)
ON DELETE RESTRICT
ON UPDATE CASCADE;
```

In this query, the language_id column in the film table is set as a foreign key referencing the language_id column in the language table. The ON DELETE RESTRICT ensures that no films can be deleted if they have a corresponding language, and ON UPDATE CASCADE updates the foreign key value if the referenced value is modified.

1. Unique Constraint:
A unique constraint ensures that the values in a column or a group of columns are unique, excluding null values. Here's an example of adding a unique constraint to the email column in the customer table:

```
ALTER TABLE customer
ADD CONSTRAINT uk_customer_email UNIQUE (email);
```

This query adds a unique constraint to the email column in the customer table, ensuring that each customer has a unique email address.

1. Check Constraint:
A check constraint is used to enforce specific conditions on the values inserted or updated in a column. Here's an example of adding a check constraint to the payment table to ensure that the amount column is greater than zero:

```
ALTER TABLE payment
ADD CONSTRAINT chk_payment_amount CHECK (amount > 0);
```

In this query, a check constraint named chk_payment_amount is added to the amount column in the payment table, ensuring that all payment amounts are greater than zero.

1. Not Null Constraint:
A not null constraint ensures that a column cannot have null values. Here's an example of adding a not null constraint to the title column in the film table:

```
ALTER TABLE film
MODIFY COLUMN title VARCHAR(255) NOT NULL;
```

This query modifies the title column in the film table to disallow null values. It ensures that every film has a non-null title.


## Using ClassicModels

```
use classicmodels;




select * from productlines;
show tables;



select productCode, productName
from products
inner join productlines USING (productLine)


select * from customers;
select * from orders;


select c.customerNumber, customerName, orderNumber, status
FROm customers c
LEFT JOIN orders o
ON c.customerNumber = o.customerNumber;

select * from orders where customerNumber = 125;


select * from customers;
select * from employees;


SELECT employeeNumber, customerNumber
from customers
RIGHT JOIN employees
ON salesRepEmployeeNumber = employeeNumber
WHERE customerNumber is NULL
ORDER BY employeeNumber;

# SELF JOIN

select * from employees;

select concat(m.lastName, ' ', m.firstName) as Manager,
concat (e.lastName, ' ', e.firstName) as 'Direct Report'
From employees e
inner join employees m
ON m.employeeNumber = e.reportsTo
ORDER BY Manager;
```
