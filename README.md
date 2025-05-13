# ♻️ Nothing Wasted – E-Waste Management System

**Nothing Wasted** is a comprehensive web-based e-wastemanagement system inspired by [erth.app](https://www.erth.app). It** is a comprehensive web-based e-waste management system inspired by [ing points that can be redeemed for rewards. Administrators can manage submissions, inventory, quotations, tracking, rewards, and more.

---

## 🌐 Live Setup Instructions

To get started:

1. Import the SQL file into your database (see below).
2. Start your local server (e.g., XAMPP).
3. Navigate to:

http://localhost/nothing_wasted/user/homepage_guest.php

All user and admin login/registration functions are handled through: user/auth.php

This file will detect whether the login is for an **admin** or a **user** and redirect accordingly.

---

## 📦 Features

### 👤 User Features

Users can:

- 🔐 **Register/Login**
- 👤 **Edit Profile**
- 🏠 **Save Up to 3 Addresses**
- 📤 **Submit E-Waste for Collection**
- 📩 **Accept/Reject Quotation**
- 💳 **Choose Payment Method** (Cash/Online)
- 🚚 **Choose Delivery Method**
  - **Pickup** by staff
  - **Drop-off** by user
- 🕓 **View Submission History**
- 🎁 **Redeem Rewards using Earned Points**

---

### 🛠️ Admin Features

Admins are categorized as:

- **Super Admin**
- **Admin**

Features include:

- 🔑 **Login with Role Detection**
- 👥 **Manage Admin Accounts**
  - Only Super Admin can edit or delete other admin accounts
- 🧮 **Edit Point Values for E-Waste Items**
  - Super Admin only
- 📬 **Accept or Reject User Submissions**
- 📑 **Generate and Send Quotations**
- 🔄 **Update Submission Tracking Status**
- 📦 **View and Manage Inventory**
- 💰 **View Payments & Generate Receipts**
- 📊 **View System Reports**
- 🎁 **Add New Rewards**
- 🗝️ **Add Redeem Keys**
- 🗃️ **View All Redeem Keys**
  - Only Super Admin has full visibility

> 🔒 **Important Notes (Do Not Delete):**
> - `set_point` record from the **`points` table`**
> - `root` record from the **`admin` table`**

---

## 🛠️ Installation & Setup

### 1. Prerequisites

- PHP 7.4+
- MySQL
- Apache Server (XAMPP or WAMP recommended)
- Web browser (Chrome or Firefox recommended)

### 2. Import SQL Database

- Locate `nothing_wasted.sql` in the `/database` folder
- Open [phpMyAdmin](http://localhost/phpmyadmin)
- Create a new database (e.g., `nothing_wasted`)
- Import the SQL file into the newly created database

### 3. Run the System

- Start your local server (Apache + MySQL)
- Go to: http://localhost/nothing_wasted/user/homepage_guest.php

### 4. Login/Signup:
- All login and registration functionality is handled via: auth.php
- It supports both admin and user login.

---------------------------------------------------------------------------------
CREDITS
--------------------------------------------------------------------------------

Developed by: Justin Chew, Lee Ken Yang, Lian Yuan Shen
Inspired by: https://www.erth.app

================================================================================
LICENSE & USAGE
================================================================================

This software is submitted as part of a Capstone Project at Asia Pacific University.
All materials are intended for academic assessment only.
Unauthorized commercial use is prohibited.
