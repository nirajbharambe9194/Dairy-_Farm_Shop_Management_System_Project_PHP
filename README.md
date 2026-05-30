# Dairy Farm Shop Management System Project (PHP)

## Project Description

The Dairy Farm Shop Management System is a web-based application developed using PHP and MySQL to manage dairy products, customer records, sales, and inventory efficiently. The system helps dairy farm owners and shop managers maintain product details, track stock levels, manage customer orders, generate bills, and monitor daily sales. It provides a user-friendly interface for managing milk, butter, cheese, curd, and other dairy products. The application reduces manual paperwork, improves inventory control, and ensures accurate record keeping through a centralized database system.

## Key Features

* User Registration and Login
* Product Management
* Inventory/Stock Management
* Customer Management
* Sales and Billing Management
* Order Tracking
* Daily and Monthly Sales Reports
* Admin Dashboard
* Secure Database Management

## Software Requirements

* XAMPP or WAMP Server
* PHP 7.0 or Above
* MySQL Database
* Web Browser (Chrome, Firefox, Edge)

## Installation and Setup

### Step 1: Install XAMPP/WAMP

1. Download and install XAMPP or WAMP Server.
2. Start Apache and MySQL services.

### Step 2: Copy Project Files

Extract the project folder and place it in:

* XAMPP: `C:\xampp\htdocs\`
* WAMP: `C:\wamp64\www\`

### Step 3: Create Database

1. Open `http://localhost/phpmyadmin`
2. Create a new database named:
   `dairy_farm_shop`

### Step 4: Import Database

1. Select the created database.
2. Click **Import**.
3. Choose the provided SQL file.
4. Click **Go**.

### Step 5: Configure Database Connection

Update the database configuration file:

```php
<?php
$host = "localhost";
$user = "root";
$password = "";
$database = "dairy_farm_shop";

$conn = mysqli_connect($host, $user, $password, $database);

if(!$conn){
    die("Connection Failed: " . mysqli_connect_error());
}
?>
```

### Step 6: Run the Project

1. Start Apache and MySQL.
2. Open a browser.
3. Visit:

`http://localhost/Dairy_Farm_Shop_Management_System_Project_PHP/`

## Modules

### Admin Module

* Manage Products
* Manage Inventory
* Manage Customers
* View Sales Reports
* Generate Bills
* Manage Orders

### Customer Module

* View Products
* Place Orders
* Check Order Status
* View Purchase History

## Database Connectivity

The system uses MySQL as the backend database. PHP MySQLi functions are used to connect the application with the database for storing and retrieving product, customer, and sales information.

## Conclusion

The Dairy Farm Shop Management System provides an efficient and automated solution for managing dairy farm shop operations. It simplifies inventory management, billing, sales tracking, and customer record maintenance, helping businesses improve productivity and accuracy while reducing manual effort.

## Unzip dist.zip & vendors.zip in same folder
