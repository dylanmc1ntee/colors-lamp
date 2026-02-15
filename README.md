# COLORS LAMP Application

## Overview

The COLORS application is a web-based CRUD system built using the LAMP stack (Linux, Apache, MySQL, PHP).  
It allows users to create, search, and manage color records stored in a MySQL database.

The application includes a frontend interface built with HTML, CSS, and JavaScript, and a backend API written in PHP that interacts with a database.

---

## Technologies Used

- PHP
- MySQL
- Apache
- HTML5
- CSS3
- JavaScript
- LAMP Stack

---

## Project Structure

colors-lamp/
│
├── LAMPAPI/        # Backend PHP API files  
├── css/            # Stylesheets  
├── images/         # Images and assets  
├── js/             # JavaScript logic  
├── index.html      # Main landing page  
├── color.html      # Color detail page  
├── .gitignore  
└── README.md  

---

## Features

- Create new color entries  
- Search for colors  
- User login functionality  
- View color details  
- Backend PHP API for database interaction  

---

## Setup Instructions

### 1. Clone the Repository

git clone https://github.com/dylanmc1ntee/colors-lamp.git

### 2. Set Up the Database

- Install MySQL (if not already installed)  
- Create a database  
- Import the required tables  

### 3. Configure Database Connection

Inside the `LAMPAPI` folder:

- Locate your configuration file  
- Update database credentials (username, password, database name)  

⚠ Database credentials are not included in this repository for security reasons.

### 4. Start Apache

If using:
- XAMPP  
- MAMP  
- WAMP  
- Docker  

Make sure Apache and MySQL are running.

### 5. Access the Application

Open your browser and navigate to:

http://localhost/index.html

---

## API Endpoints

The backend PHP files inside `LAMPAPI/` handle:

- AddColor.php – Adds a new color  
- SearchColors.php – Searches for colors  
- Login.php – Handles user login  

These endpoints are called using JavaScript (fetch requests) from the frontend.

---

## Assumptions and Limitations

- Designed for local development  
- No production deployment configuration  
- Basic validation only  
- Authentication is session-based  

---

## License

This project is licensed under the MIT License.
