# Cashier-App
This repository contains code for a cashier application built using the Flet framework. The application allows cashiers to manage orders, view menus, and perform various cashier-related tasks.

Overview
The Cashier App is a Python-based application developed using the Flet framework, which provides a simple and flexible way to create graphical user interfaces (GUIs). Here's an overview of the key components and features of the application:

Login Page: Users (cashiers) are required to log in with their username and password before accessing the application. The login credentials are verified against a SQLite database.

Home Page: After successful login, users are greeted with the home page, where they can navigate to different sections of the application, including the menu, billing, and settings.

Menu Page: Cashiers can view the menu items available for ordering. The menu data is fetched from an SQLite database and displayed in a tabular format.

Billing Page: Cashiers can add items to a cart, generate bills, and view the total amount to be paid. The application calculates the total bill amount, applies a GST (Goods and Services Tax) rate, and displays the final bill.

Settings Page: Cashiers can access settings to perform various tasks, such as updating product prices, adding new products to the menu, deleting products, and updating the GST rate.

Receipt Page: A receipt page is available to display transaction details and provide a summary of the order.

Usage
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/cashier-app.git
Navigate to the project directory:

bash
Copy code
cd cashier-app
Ensure you have the required Python libraries installed:

bash
Copy code
pip install flet
Run the application:

bash
Copy code
python main.py
Access the application by opening a web browser and navigating to http://localhost:5000.

Features
User Authentication: Cashiers are required to log in with their credentials, which are verified against a SQLite database.

Menu Display: The application fetches menu items from the database and displays them in a user-friendly format.

Billing and Receipt: Cashiers can add items to a cart, generate bills, and view receipts. The application calculates and displays the total amount to be paid, including GST.

Settings Management: Cashiers can perform various settings-related tasks, such as updating product prices, adding new products to the menu, deleting products, and updating the GST rate.

Database
The application uses an SQLite database (sql.db) to store and manage data related to cashiers, menu items, and transactions.

Dependencies
The main dependencies for this project include the following:

flet: The Flet framework is used to create the graphical user interface.
sqlite3: SQLite is used for database operations.
Screenshots
Here are some screenshots of the Cashier App:

Login Page

Home Page

Menu Page

Billing Page

Settings Page

Receipt Page
