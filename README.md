Here are step-by-step instructions for a PHP form registration task:

1. **File Location**: Begin by copying the attached file to your local directory. Store the file at a location like `C:\xampp\htdocs\home`. This location will serve as your project directory.

2. **XAMPP Setup**: Ensure that your XAMPP server is up and running, including Apache and MySQL.

3. **Database Creation**:

   - Access your PHPMyAdmin interface by navigating to `http://localhost/phpmyadmin` in your web browser.
   - Create a new database named `form_data`.
   - Inside the `form_data` database, create a table named `users` with the following columns:
     - `id` (Auto-increment, Primary Key)
     - `first_name` (VARCHAR 50)
     - `last_name` (VARCHAR 50)
     - `email` (VARCHAR 20)
     - `phone_no` (VARCHAR 20)
     - `password` (VARCHAR 50)
     - `gender` (VARCHAR 10)

4. **Database Connection**:

   - In the `connection.php` file within your project directory, update the following details:
     - `servername`: Set this to the MySQL server's address (usually "localhost" for local development).
     - `username`: Your MySQL username.
     - `password`: Your MySQL password.
     - `database_name`: Set this to "form_data" to connect to the database you just created.

5. **Accessing the File**:
   - To access your registration form, open a web browser and enter the following URL: `http://localhost/home/home.php`.
   - This URL will take you to the registration form where users can submit their information.
