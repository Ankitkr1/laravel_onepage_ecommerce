# laravel_onepage_ecommerce
Welcome to the E-Commerce Application! This application is a single-page e-commerce platform developed using PHP, AJAX, and JavaScript with PayPal payment.
instructions for setting up and running the application on your local server.

Setup Instructions
Start XAMPP Server: Ensure that your XAMPP server is running before proceeding with the setup.
Extract Files: Extract the contents of the provided project zip file into the htdocs directory of your XAMPP server.
Create Database: Open your preferred database management tool (e.g., phpMyAdmin) and create a new database named webmantra_db.
Run Migrations and Seed Data: Open your terminal or command prompt, navigate to the root directory of the project, and execute the following commands:
php artisan migrate
php artisan db:seed --class=ProductSeeder

Start Application: To run the application, navigate to the root directory of the project in your terminal or command prompt and execute the following command:

php artisan serve
Access the Application: Once the server is running, open your web browser and go to http://localhost:8000 to access the WebMantra E-Commerce Application.

Features
Product Display: View and add products to your cart without refreshing the page.
Cart Functionality: Utilizes a modal for adding products to the cart.
Billing Details: Users can fill in their billing details, including name, address, and email.
Payment Processing: Integrated with PayPal Sandbox for secure payment processing.
Order Confirmation: Users are redirected to a "Thank You for Your Order" page after successful payment.
Order failure page Users are redirected to a "Order failure page" page after Failed payment.
Technologies Used
PHP
AJAX
JavaScript
Laravel Framework
