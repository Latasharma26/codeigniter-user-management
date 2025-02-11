# CodeIgniter 3 User Management System

This is a simple User Management System built with CodeIgniter 3. It includes features like listing users, adding, editing, and deleting users.

## Features
- List all users
- Add a new user
- Edit user details
- Delete a user
- Styled with CSS for better UI

## Installation

### 1. Clone the repository:
```sh
git clone https://github.com/your-username/codeigniter-user-management.git
cd codeigniter-user-management

2. Setup Database:
Create a database in MySQL (e.g., ci_user_management).
Import database.sql (if provided).
Configure database in application/config/database.php:
php
Copy
Edit
$db['default'] = array(
    'dsn'   => '',
    'hostname' => 'localhost',
    'username' => 'root',
    'password' => '',
    'database' => 'ci_user_management',
    'dbdriver' => 'mysqli',
);
3. Configure Base URL:
Open application/config/config.php and update:
php
Copy
Edit
$config['base_url'] = 'http://localhost/ci/';
4. Run the Application:
Start Apache and MySQL in XAMPP
Open your browser and go to:
ruby
Copy
Edit
http://localhost/ci/index.php/user
