# ESHOP - Innovative Tech E-Commerce Platform

ESHOP is a modern, user-friendly, and feature-rich e-commerce web application specifically engineered for tech enthusiasts, students, and professionals. The platform provides a seamless digital shopping experience akin to visiting a physical technology store, allowing users to effortlessly browse, evaluate, and securely purchase the latest tech hardware, smartphones, and accessories[cite: 1].

---

## 🚀 Core Features

### 🛒 Customer Experience
* **Advanced User Authentication**: Secure Sign-Up and Sign-In forms equipped with client-side validation and responsive selector options[cite: 1].
* **Forgot Password Recovery**: Interactive password recovery system utilizing automated security verification codes sent via email to allow secure password resets[cite: 1].
* **Dynamic Homepage & Advanced Discovery**: Fully structured product categories featuring dedicated sections for Laptops, Desktop Computers, Processors, Motherboards, Graphic Cards, Storage, Memory (RAM), Power Supplies, Cooling Systems, Casings, Monitors, and Speakers[cite: 1].
* **Personalized User Dashboard**: 
  * View and manage personal profile configurations, shipping addresses, and contact parameters[cite: 1].
  * Detailed order tracking and historical transaction logs[cite: 1].
  * Interactive **Watchlist** and **Cart** systems to easily save and queue items for faster checkouts[cite: 1].
* **Real-time Messaging**: Built-in chat overlay allowing direct communication channels for continuous user engagement[cite: 1].

### 🛠️ Product & Store Management
* **Vendor/User Product Operations**: Seamlessly upload and modify product listings with explicit controls for product category, brand, model, color, quantity, physical condition, item cost, shipping costs, descriptive overviews, and product images[cite: 1].
* **Advanced Search & Filtering**: Client-side filtering systems sorting products by active duration (newest to oldest), condition (brand new or used), and pricing trends (low-to-high or high-to-low)[cite: 1].

### 👑 Comprehensive Administrative Controls
* **User & Category Administration**: Dedicated management panels to oversee all registered platform users (with option blocks) and dynamic management of inventory categories[cite: 1].
* **Analytical Admin Dashboard**: Real-time business intelligence metrics including tracking for Daily Earnings, Monthly Earnings, Today's Sellings, Cumulative Sellings, Total Platform Engagement, Active Store Time, and predictive blocks showcasing "Mostly Sold Items" alongside "Most Famous Sellers"[cite: 1].

---

## 🛠️ Architecture & Core Structure

The application's interface layout is structurally divided into logical UI modules for clean maintainability:
* **Authentication Modules**: User Registration, Login Interface, Secure Verification Code Modal, and Admin Authentication Gateways[cite: 1].
* **Product Management Views**: Store Listings, Individual Profiles, Product Addition Forms, Category Customization Canvas, and Global Product Inventories[cite: 1].
* **Engagement Interfaces**: Interactive Shopping Cart, Customer Watchlists, Direct Admin-User Message Logs, and Central Analytical Command Dashboards[cite: 1].

---

## 🔒 Security Standards

* **Data Entry Integrity**: Multi-tier data field input validation on account creation and product updates[cite: 1].
* **Administrative Isolation**: Role-based access pathways ensuring back-end system metrics and user lists are exclusively restricted to certified administrators[cite: 1].
* **Session Integrity & Management**: Implementation of specialized access modes and status monitoring for active platform operations[cite: 1].

---

## 💻 Tech Stack

### Frontend & UI
* **HTML5 & CSS3**: Core application structure and custom UI styling.
* **JavaScript (ES6+)**: Client-side logic, real-time input validations, search filtering, and interactive UI components[cite: 1].
* **Bootstrap**: Responsive UI layout framework ensuring mobile and desktop compatibility[cite: 1].

### Backend & Database
* **PHP**: Server-side scripting language handling business logic, user authentication, and data routing[cite: 1].
* **MySQL**: Relational database management system for storing user profiles, product catalogs, and order history[cite: 1].

---

## 🚀 How to Run the Project Locally

Follow these steps to set up and run the e-commerce platform on your local machine:

### Prerequisites
Make sure you have a local web server environment installed, such as **XAMPP**, **WAMP**, or **MAMP**.

### Step 1: Clone or Copy the Project
1. Download or clone the project source code.
2. Move the project folder into your server's root directory:
   * **XAMPP**: `C:\xampp\htdocs\`
   * **WAMP**: `C:\wamp64\www\`

### Step 2: Set Up the Database
1. Open your browser and navigate to **phpMyAdmin** (`http://localhost/phpmyadmin`).
2. Create a new database (e.g., name it `eshop`).
3. Select the newly created database, go to the **Import** tab, and upload the `.sql` file provided inside the project folder to set up all the required tables and data structures[cite: 1].

### Step 3: Configure Connection
1. Open the project folder in your code editor.
2. Locate the database connection configuration file (usually named `connection.php` or similar).
3. Update the database credentials to match your local environment settings:
```php
   $host = "localhost";
   $username = "root"; 
   $password = ""; // Default is empty for XAMPP
   $database = "eshop"; // Your database name


   <!-- Testing for Pull Shark badge -->