MYCRUD.ZIP-  PHP CRUD Application;


This is a simple PHP CRUD application that allows you to perform basic Create, Read, Update, and Delete operations on a database.
Features
* Create: Add new records to the database.
* Read: Retrieve and display records from the database.
* Update: Modify existing records in the database.
* Delete: Remove records from the database.
Technologies Used
* PHP: The server-side scripting language used for handling the CRUD operations and interacting with the database.
* MySQL: The relational database management system used to store and retrieve data.
Installation
1. Clone the repository:
2. Set up the Database:
    * Create a new database in MySQL.
    * Modify the database connection details in the config.php file to match your MySQL database configuration.
3. Import the SQL File:
    * Import the provided SQL file myCRUD_dbsql into your newly created database. This file contains the necessary table structure.
4. Run the Application:
    * Ensure you have PHP installed on your system.
    * Navigate to the project directory.
    * Start a PHP development server:
5. Access the CRUD Operations:
    * Use a tool like Postman or cURL to send HTTP requests and perform CRUD operations on the endpoints provided by the PHP files.
    * Refer to the PHP files in the project for the specific endpoints and their corresponding HTTP methods.
Usage
* Each CRUD operation corresponds to a specific PHP file in the project.
* Use POST requests to create new records.
* Use GET requests to retrieve records.
* Use PUT or PATCH requests to update existing records.
* Use DELETE requests to remove records.
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to create a pull request or submit an issue.
