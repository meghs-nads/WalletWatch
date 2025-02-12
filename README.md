# WalletWatch

## Overview
The **WalletWatch** is a web-based application built using PHP and MySQL. It allows users to track their daily expenses, manage categories, and generate reports to analyze their spending habits.

## Features
- **User Authentication**: Secure login, registration, and password reset.
- **Expense Management**: Add, edit, and delete expenses.
- **Expense Reports**: View expenses by date, month, and year.
- **User Profile**: Manage user information and change passwords.
- **Dashboard**: Overview of expenses with summaries and insights.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP, MySQL
- **Additional**: Bootstrap for UI, AJAX for smooth interactions

## Installation Guide
### Step 1: Clone the repository
```sh
git clone https://github.com/meghs-nads/WalletWatch.git
```
### Step 2: Navigate to the project folder
```sh
cd WalletWatch/dets
```
### Step 3: Import the database
- Locate the `db.sql` file in the project.
- Import it into your MySQL database using phpMyAdmin or MySQL CLI.

### Step 4: Configure database connection
- Open `config.php` and update the database credentials:
```php
$host = "your_host";
$user = "your_user";
$password = "your_password";
$database = "your_database";
```

### Step 5: Start a local server (e.g., XAMPP, WAMP, or MAMP) and place the project in the `htdocs` folder.

### Step 6: Open the application in your browser
```sh
http://localhost/dets/index.php
```

## Folder Structure
```plaintext
Wallet Watch
│── dets
│   ├── index.php  (Main entry point)
│   ├── dashboard.php  (User dashboard)
│   ├── add-expense.php  (Add expenses)
│   ├── manage-expense.php  (View and manage expenses)
│   ├── user-profile.php  (Profile management)
│   ├── logout.php  (User logout)
│   ├── assets/ (CSS, JS, images)
│   └── config.php  (Database connection - Do not commit sensitive data)
│── db.sql  (Database schema - Import this into MySQL)
│── README.md  (Project documentation)
```



