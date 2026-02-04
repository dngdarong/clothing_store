# clothing_store
"# clothing_store" 
# Admin Module – Clothing Store System

## Overview

The **Admin Module** is a secure dashboard for managing the clothing store system.  
It allows administrators to control products, users, categories, and orders using a Vue frontend connected to a Laravel API backend.

This module is designed for store owners and staff to maintain inventory, monitor sales, and manage the platform efficiently.

---

## Features

### Authentication
- Secure admin login
- Token-based authentication (Laravel Sanctum)
- Role-based access control (admin / user)

### Dashboard
- Quick overview of store system
- Navigation to all management modules

### Product Management
- Add new products
- Edit existing products
- Delete products
- Upload product images
- Assign categories
- Manage pricing and descriptions

### Category Management
- Create categories
- Update categories
- Delete categories
- Organize product groups

### User Management
- Create admin or user accounts
- Edit user information
- Delete users
- Assign roles (admin / user)

### Order Management
- View all customer orders
- Update order status
- Delete or manage orders
- Track order history

### Profile & Settings
- Update admin profile
- Upload avatar
- Manage account information

---

## Technology Stack

- **Frontend:** Vue 3 + Tailwind CSS
- **Backend:** Laravel API
- **Authentication:** Laravel Sanctum
- **Database:** MySQL
- **Routing:** Vue Router
- **HTTP Client:** Axios

---

## Security

- Protected API routes using middleware
- Admin-only access control
- Token authentication
- Backend input validation
- Role-based permissions

---

## Purpose

The admin module helps administrators:

- Maintain store inventory
- Manage user accounts
- Monitor customer orders
- Keep store data organized
- Operate the shop efficiently

---

## Installation

### Backend (Laravel)

```bash
git clone <backend-repo>
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

### Frontend (Vue)

```bash
cd frontend
npm install
npm run dev
```

---

## Author

Clothing Store Admin System  
Built for learning and real-world shop management.

