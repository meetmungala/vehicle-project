# 🚗 Vehicle Breakdown Assistance Management System

A full-featured **PHP & MySQL** web application that streamlines vehicle breakdown assistance — connecting users in distress with nearby drivers and an admin control panel.

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Default Credentials](#default-credentials)
- [Database Setup](#database-setup)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## 📌 About the Project

The **Vehicle Breakdown Assistance Management System** is a web-based platform designed to help users who face vehicle breakdowns on the road. Users can raise a service request, and drivers can accept and respond to those requests. Admins have full control over the system — managing users, drivers, and requests from a dedicated panel.

---

## ✨ Features

### 👤 User Panel
- Register and log in as a user
- Raise a vehicle breakdown request
- Track request status in real-time

### 🚘 Driver Panel
- Log in as a driver
- View and accept assigned breakdown requests
- Manage service history

### 🛠️ Admin Panel
- Manage users and drivers
- View and handle all breakdown requests
- Dashboard with system overview

### 💎 Design & UI
- Modernized layout with polished CSS aesthetics
- Fully responsive design optimized for mobile and desktop views

---

## 🛠 Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | HTML5, CSS3, JavaScript, Bootstrap |
| Backend      | PHP (Core PHP)     |
| Database     | MySQL              |
| Local Server | XAMPP / WAMP / LAMP |

---

## 📁 Project Structure

```
Vehicle-Breakdown-Assistant-main/
│
├── SQL File/
│   └── vehassitancemsdb.sql        # Database schema & seed data
│
├── vehicleassitancems/             # Main application folder
│   ├── index.php                   # Landing / Home page
│   ├── about-us.php                # About page
│   ├── contact.php                 # Contact page
│   ├── booking-request.php         # User breakdown request form
│   ├── admin/                      # Admin panel pages
│   ├── driver/                     # Driver panel pages
│   ├── includes/                   # DB config & common includes
│   ├── assets/                     # Images, icons & media
│   ├── css/ & css1/                # Stylesheets
│   ├── js/                         # JavaScript files
│   ├── fonts/                      # Font files
│   └── lib/                        # Third-party libraries
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- [XAMPP](https://www.apachefriends.org/) / [WAMP](https://www.wampserver.com/) / LAMP installed
- PHP >= 7.x
- MySQL >= 5.x
- A modern web browser

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Vehicle-Breakdown-Assistant.git
   ```

2. **Copy the application folder**
   - Copy the `vehicleassitancems` folder into your server root:
     - **XAMPP**: `C:/xampp/htdocs/`
     - **WAMP**: `C:/wamp/www/`
     - **LAMP**: `/var/www/html/`

3. **Set up the database** *(see [Database Setup](#database-setup) below)*

4. **Run the application**
   - Open your browser and navigate to:
     ```
     http://localhost/vehicleassitancems
     ```

---

## 🗄️ Database Setup

1. Open **phpMyAdmin**: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
2. Create a new database named **`vehassitancemsdb`**
3. Import the SQL file located at:
   ```
   SQL File/vehassitancemsdb.sql
   ```
4. The database will be populated with the required tables and demo data.

---

## 🔐 Default Credentials

> ⚠️ **Change these credentials after your first login!**

| Role   | Username  | Password   |
|--------|-----------|------------|
| Admin  | `admin`   | `Test@123` |
| Driver | `test123` | `Test@123` |
| User   | Register a new account via the frontend |

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 📬 Contact

For queries or support, feel free to open an issue or reach out through the [contact page](http://localhost/vehicleassitancems/contact.php) of the application.

---

> Made with ❤️ using PHP & MySQL
