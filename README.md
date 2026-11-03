# 🍔 Campus Food Ordering System

A web-based food ordering and canteen management system designed for university students and campus food services.

The system provides an online platform where customers can browse food items, manage shopping carts, place orders, and make payments.

Built with **PHP, MySQL, and Domain-Driven Design (DDD)** principles.

## 📌 Project Overview

The Campus Food Ordering System aims to simplify food ordering within a university campus by providing a convenient digital platform for customers, staff, and administrators.

The system separates application responsibilities into different modules to improve maintainability, organization, and scalability.

## ✨ Key Features

- **User Management** – User registration, login, authentication, and access control.
- **Food Management** – Manage food items and food-related information.
- **Shopping Cart** – Add, update, and manage food items in the cart.
- **Order Management** – Place orders and manage order information.
- **Payment Management** – Handle payment-related operations.
- **Refund Management** – Manage refund requests and processes.
- **Admin Dashboard** – Administrative management features.
- **Staff Dashboard** – Staff-related operations.
- **Notifications** – Provide notifications to users.
- **Email Verification** – Support account verification and password recovery.
- **Google Authentication** – Google OAuth integration.
- **Receipt Generation** – Generate printable order receipts.

## 🛠️ Technologies Used

| Technology        | Purpose                       |
| ----------------- | ----------------------------- |
| PHP               | Backend development           |
| MySQL             | Database management           |
| HTML5             | Web page structure            |
| CSS3              | Styling                       |
| JavaScript        | Frontend interactions         |
| Composer          | PHP dependency management     |
| PHPMailer         | Email functionality           |
| Google API Client | Google OAuth integration      |
| Dompdf            | PDF receipt generation        |
| Apache            | Local web server              |
| XAMPP             | Local development environment |

## 🏗️ Project Structure

```text
Campus-Food-Ordering-System/
│
├── App/
│   ├── AccessControl/
│   ├── Cart/
│   ├── Food/
│   ├── Kernel/
│   ├── Notification/
│   ├── Order/
│   ├── Payment/
│   ├── Refund/
│   ├── Router/
│   ├── Security/
│   ├── Shared/
│   └── User/
│
├── inc/
│   ├── config/
│   ├── Database.php
│   └── helper files
│
├── Public/
│   ├── api/
│   ├── uploads/
│   ├── index.php
│   └── landing.php
│
├── routes/
│   └── web.php
│
├── view/
│   ├── admin/
│   ├── components/
│   ├── customer/
│   ├── entrance/
│   ├── maintenance/
│   ├── notifications/
│   └── staff/
│
├── vendor/
│
├── composer.json
├── composer.lock
└── database1.sql
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/htet-nandar-winn/Campus-Food-Ordering-System.git
```

### 2. Navigate to the Project

```bash
cd Campus-Food-Ordering-System
```

### 3. Install Dependencies

Make sure PHP and Composer are installed.

```bash
composer install
```

### 4. Set Up the Database

1. Start Apache and MySQL from the XAMPP Control Panel.
2. Open phpMyAdmin.
3. Create a new database named:

```text
campus_food_ordering_system1
```

4. Select the newly created database.
5. Import the `database1.sql` file.

### 5. Configure Database Connection

Open the following file:

```text
inc/Database.php
```

Update the database credentials according to your local MySQL configuration.

```php
private static string $host = '127.0.0.1';
private static string $dbname = 'campus_food_ordering_system1';
private static string $user = 'root';
private static string $pass = 'your_mysql_password';
```

### 6. Run the Project

Place the project inside your XAMPP `htdocs` directory.

Start Apache and MySQL, then open your browser and visit:

```text
http://localhost/Campus-Food-Ordering-System/Public/
```

## 📦 Requirements

- PHP 8.0 or later (check Composer package requirements for the exact supported version).
- MySQL or MariaDB.
- Apache Web Server.
- Composer.
- XAMPP.

## 🎯 Project Objectives

- Make campus food ordering more convenient.
- Reduce manual food ordering processes.
- Improve order management and tracking.
- Provide an organized platform for customers, staff, and administrators.
- Apply modular software architecture principles.
- Improve the maintainability and scalability of the application.

## 👩‍💻 Developer

**Htet Nandar Winn**

- **GitHub Profile:** [Htet Nandar Winn](https://github.com/htet-nandar-winn)

---

⭐ If you find this project interesting, feel free to explore the repository!
