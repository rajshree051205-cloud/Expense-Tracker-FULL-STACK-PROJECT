💰 Expense Tracker — Full Stack Project

A simple, modern, and responsive Expense Tracker Web Application built using PHP, MySQL, HTML, CSS, JavaScript, and Chart.js.

The application allows users to add, view, manage, and delete expenses while providing a visual overview of spending through interactive charts.

✨ Features

➕ Add new expenses

🗑️ Delete expenses

📊 Visualize expenses using Chart.js

💰 Calculate total expenses

📋 View all recorded expenses

🏷️ Organize expenses by category

📅 Track expenses by date

📝 Add expense descriptions

🗄️ Store expense data in MySQL

📱 Responsive and clean user interface

⚡ Simple PHP-based backend

🛠️ Technologies Used

HTML5 — Structure of the application

CSS3 — Styling and responsive layout

JavaScript — Client-side functionality

Chart.js — Expense visualization and graphs

PHP — Backend and expense management

MySQL — Database storage

XAMPP — Local development environment

📂 Project Structure

The project currently keeps all main files in the root directory for simplicity.

Expense-Tracker-FULL-STACK-PROJECT/
│
├── LICENSE
├── README.md
├── Schema.sql
├── db_connect.php
├── index.php
├── process.php
├── script.js
└── style.css

File Description
File	Description
index.php	Main page and Expense Tracker interface
process.php	Handles expense-related backend operations
db_connect.php	Connects the application to the MySQL database
Schema.sql	Contains the database and table structure
script.js	Handles frontend interactions and Chart.js functionality
style.css	Contains the styling and responsive layout
README.md	Project documentation
LICENSE	Project license
📊 Expense Visualization

The project uses Chart.js to display expense data graphically.

The chart helps users understand their spending by displaying expenses based on categories.

For example:

Food
Travel
Shopping
Bills
Entertainment
Healthcare
Education
Other


This makes it easier to identify where most of the money is being spent.

💾 Database

The application uses MySQL to store expense information.

The database structure is provided in:

Schema.sql


The expense records contain information such as:

Expense title

Amount

Category

Date

Description

Created date

⚙️ How to Run the Project
1. Clone the Repository
git clone https://github.com/rajshree051205-cloud/Expense-Tracker-FULL-STACK-PROJECT.git


Or download the repository as a ZIP file from GitHub.

2. Move the Project to XAMPP

If you are using XAMPP, place the project inside:

C:\xampp\htdocs\


The final path should look like:

C:\xampp\htdocs\Expense-Tracker-FULL-STACK-PROJECT\

3. Start XAMPP

Open XAMPP Control Panel and start:

Apache
MySQL

4. Create the Database

Open phpMyAdmin:

http://localhost/phpmyadmin


Create a database for the project.

For example:

expense_tracker


Then import the SQL file:

Schema.sql

5. Configure Database Connection

Open:

db_connect.php


Make sure the database connection details match your local MySQL configuration.

Example:

$host = "localhost";
$user = "root";
$password = "";
$database = "expense_tracker";


If your MySQL username, password, or database name is different, update the values accordingly.

6. Run the Application

Open your browser and visit:

http://localhost/Expense-Tracker-FULL-STACK-PROJECT/


The Expense Tracker dashboard should now be available.

➕ Add an Expense

Users can add a new expense by providing information such as:

Title

Amount

Category

Date

Description

After submitting the form, the expense is processed by the PHP backend and stored in the MySQL database.

🗑️ Delete an Expense

The application also provides a delete option for recorded expenses.

When an expense is deleted, the corresponding record is removed from the database and the expense list is updated.

📈 Expense Chart

The application uses Chart.js to create a visual representation of the stored expenses.

The chart updates according to the expense information available in the application, allowing users to get a quick overview of their spending.

🎨 Design

The interface focuses on keeping expense management simple and easy to understand.

The project includes:

Clean dashboard layout

Responsive design

Expense cards/table

Interactive chart

Simple navigation

Clear action buttons

User-friendly expense form

🔮 Future Improvements

The project can be extended with additional features in future versions:

✏️ Edit existing expenses

🔎 Search expenses

🔽 Filter expenses by category

📅 Filter expenses by date

👤 User registration and login

🔐 Authentication

🌙 Dark mode

📥 Export expenses to CSV

📄 Generate expense reports

📊 Monthly and yearly analytics

💰 Budget tracking

🔔 Budget notifications

☁️ Online deployment

🧑‍💻 Author

Rajshree

GitHub: rajshree051205-cloud

📄 License

This project is open source and available under the MIT License.

See the LICENSE file for more information.

⭐ Show Your Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.

Built with ❤️ using PHP, MySQL, JavaScript & Chart.js
