# PHP MySQL Connection with PDO

This project demonstrates how to establish a connection to a MySQL database using PHP's PDO (PHP Data Objects). PDO provides a secure and flexible way to interact with databases in PHP.

## Features

- **Database Connection**: Establishes a connection to a MySQL database using the PDO extension.
- **Error Handling**: PDO is set to throw exceptions if an error occurs during the connection or database operations.
- **UTF-8 Encoding**: The connection ensures that all interactions with the database use UTF-8 encoding, which is important for handling special characters and internationalization.

## Requirements

- **PHP**: Ensure you have PHP installed (version 5.1 or newer is recommended).
- **MySQL**: A MySQL server must be running on the host specified in the configuration.
- **PDO Extension**: Ensure the `pdo_mysql` extension is enabled in your PHP configuration.

## Configuration

You can configure the connection parameters in the PHP script:

```php
// Database configuration
$host = 'localhost';  // Hostname of the database server
$port = 3306;         // Port number for the MySQL service
$dbName = 'blog';     // Name of the database you want to connect to
$username = 'root';   // MySQL username
$password = '';       // MySQL password
