Xshop_FPT

Overview

This project is a web-based e-commerce platform developed using PHP. The application allows users to browse, purchase, and manage products efficiently. It also provides administrators with tools to manage products, orders, customers, and promotional offers. The goal is to deliver a robust and user-friendly shopping experience.

Features

For Customers:

Product Catalog: Browse and search for products by category or keyword.

Shopping Cart: Add, remove, and modify items before checkout.

Checkout Process: Seamless checkout with secure payment processing.

Profile Management: View and update personal information.

Order Tracking: Track the status of placed orders.

For Admins:

Product Management: Add, edit, delete, and manage product inventory.

Order Management: View and update the status of customer orders.

Customer Management: Manage customer information and purchase history.

Promotions and Discounts: Create and manage discount codes and promotional offers.

Analytics and Reporting: View statistical data such as sales revenue, order counts, and top-selling products.

Technologies Used

Backend: PHP (Core PHP or MVC architecture)

Frontend: HTML, CSS, JavaScript (Bootstrap for responsive design)

Database: MySQL for data storage and management

Email Services: PHPMailer for email functionality (e.g., password recovery)

Charting: Libraries for data visualization (e.g., Chart.js)

Hosting: XAMPP or Laragon for local development

Installation and Setup

Prerequisites:

PHP 7.4 or higher

MySQL 5.7 or higher

Composer (optional, if dependencies are managed)

XAMPP, Laragon, or any compatible local server

Steps:

Clone the repository:

git clone https://github.com/your-repo/web-shop.git

Set up the database:

Import the database.sql file located in the /db directory into your MySQL server.

Update database credentials in the configuration file (e.g., config/database.php).

Start the local server:

Place the project folder in the server’s htdocs (XAMPP) or www (Laragon) directory.

Run the server and navigate to http://localhost/web-shop.

Configure PHPMailer:

Update SMTP settings in the email configuration file to enable email functionality.

Usage

Customer Access:

Register for a new account or log in with existing credentials.

Browse products and add items to the shopping cart.

Proceed to checkout to complete the purchase.

View order history and manage account information in the profile section.

Admin Access:

Log in with admin credentials.

Manage products, orders, customers, and promotions via the admin dashboard.

View analytics and generate reports.

Folder Structure

/web-shop
|-- /config           # Configuration files (database, email, etc.)
|-- /controllers      # Application logic controllers
|-- /models           # Database interaction models
|-- /views            # Frontend templates
|-- /public           # Public assets (CSS, JS, images)
|-- /db               # Database files
|-- /vendor           # Dependencies (if using Composer)
|-- index.php         # Entry point for the application
|-- README.md         # Project documentation

Future Enhancements

Integrate payment gateways for secure transactions.

Implement advanced search with filters and sorting.

Add multi-language and multi-currency support.

Develop a mobile-friendly app version.

Incorporate machine learning for personalized recommendations.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Contributors

[ancqph51578] - Developer

[ancqph51578] - Designer
