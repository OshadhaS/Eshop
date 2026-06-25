# EShop - E-Commerce Web Application

A comprehensive, responsive, and secure E-Commerce web platform built to deliver a seamless online shopping experience. This project features a robust user authentication ecosystem, a dynamic store interface, and an advanced admin management system.

---

## 🚀 Key Features

### 🔐 Advanced User Authentication System
* **User Registration & Login:** Secured with unique validation workflows (`signUpProcess.php`, `signInProcess.php`).
* **Secure Verification:** Email-based verification mechanisms for enhanced user security (`verificationProcess.php`).
* **Password Management:** Complete forgot-password and secure reset-password loop implemented smoothly (`forgotPasswordProcess.php`, `resetPasswordProcess.php`).
* **User Profiles:** Customizable user settings and profile management layouts (`userProfile.php`).

### 🛒 Core E-Commerce Flows
* **Product Catalog:** Interactive search using basic and multi-layered advanced search algorithms (`advancedSearch.php`, `basicSearchProcess.php`).
* **Cart & Watchlist Management:** Seamlessly add, view, or remove products from the user's shopping cart and watchlist (`cart.php`, `watchlist.php`).
* **Instant Purchase:** Streamlined checkout process with instant invoice generation and historical logging (`buyNowProcess.php`, `saveInvoice.php`).
* **Transaction Histories:** Full visibility for users regarding their purchases and sales history (`purchasingHistory.php`, `sellingHistory.php`).

### 🛠️ Robust Admin Panel & Dashboard
* **Secure Admin Access:** Separate portal for administration with standalone verification processes (`adminPanel.php`, `adminSignIn.php`).
* **User & Product Moderation:** Block or unblock users, manage active products, and monitor user listings (`manageUsers.php`, `manageProduct.php`).
* **Internal Messaging:** Directly communicate with users or view user queries (`sendAdminMessageProcess.php`, `viewMsgProcess.php`).

---

## 🛠️ Tech Stack Used

* **Frontend:** HTML5, CSS3, Bootstrap 5 (Responsive Layouts)
* **Backend:** PHP (Procedural/Object-Oriented Server-Side Logic)
* **Database:** MySQL (Relational Database Management)
* **Server Environment:** XAMPP (Apache Server & phpMyAdmin)
* **Third-Party Libraries:** PHPMailer (SMTP Email Integrations for verification/resets)

---

## ⚙️ How to Setup & Run Locally

Since this setup utilizes an Apache/MySQL bundle like XAMPP, follow these quick steps to get it running:

1. **Clone or Download the Project:**
   Place the project files directly into your XAMPP local server directory:
   `C:\xampp\htdocs\ESHOP_PROJECT\` (or equivalent path on macOS).

2. **Configure the Database:**
   * Open XAMPP Control Panel and start **Apache** and **MySQL**.
   * Open your web browser and navigate to `http://localhost/phpmyadmin/`.
   * Create a new database.
   * Import the project's SQL dump file (if available) to restore all required tables and relationships.
   * Verify database configuration inside `connection.php`.

3. **Launch the Application:**
   * Open your browser and navigate to: `http://localhost/ESHOP_PROJECT/index.php`