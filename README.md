# 🛒 AI-Powered E-Commerce Platform

A full-stack e-commerce web application built with Laravel 10, featuring secure authentication, payment gateway integration, RESTful APIs, admin dashboard, and an AI-powered customer support chatbot.

## 🚀 Live Demo

* Portfolio: https://silvy-portfolio.vercel.app
* Repository: https://github.com/silvyph/ecommerce-api
* Deployment: Alwaysdata Hosting

---

## 📌 Project Overview

This project was developed to simulate a modern e-commerce ecosystem with complete customer and admin workflows.

The application includes:

* Product catalog and shopping cart
* Secure authentication with Google OAuth
* Payment processing using Xendit
* Admin dashboard for business management
* RESTful APIs for future mobile integration
* AI-powered chatbot using Gemini API
* Real-time payment status updates via webhook

---

## ✨ Key Features

### Customer Features

* Browse products by category
* Product detail pages
* Shopping cart management
* User registration and login
* Google OAuth authentication
* Secure checkout process
* Order history tracking
* AI chatbot customer support

### Admin Features

* Product Management (CRUD)
* Order Management
* User Management
* Category Management
* Sales Monitoring Dashboard
* Business Reporting

### API Features

* RESTful API Architecture
* Laravel Sanctum Authentication
* Product APIs
* Payment APIs
* Chatbot APIs

### Security Features

* Role-Based Access Control (RBAC)
* Laravel Sanctum Token Authentication
* Google OAuth Authentication
* Xendit Webhook Validation
* Protected Admin Routes

---

## 💡 Technical Highlights

### Xendit Payment Integration

Integrated Xendit payment gateway to generate invoices and process customer payments.

### Webhook-Based Payment Synchronization

Automatically updates order status after receiving payment notifications from Xendit.

### AI Customer Support Chatbot

Implemented customer support chatbot using Gemini API to answer product-related questions and improve user experience.

### RESTful API Development

Developed API endpoints to support future mobile application integration.

### Dual Database Architecture

Separated authentication and e-commerce data using multiple database connections.

### Deployment Experience

Successfully deployed and configured the application on Alwaysdata Hosting.

---

## 🖼️ Application Screenshots

### Home Page

![Homepage](screenshots/homepage.png)

### Product Catalog

![Product Catalog](screenshots/produk_katalog.png)

### Shopping Cart & Checkout

![Shopping Cart](screenshots/shoppingcart.png)

### Admin Dashboard

![Admin Dashboard](screenshots/admin_dashboard.png)

### AI Chatbot

![AI Chatbot](screenshots/chatbot.png)

---

## 🔄 System Workflow

### Customer Flow

1. Browse products
2. Add items to cart
3. Authenticate using Email or Google OAuth
4. Checkout
5. Generate invoice via Xendit
6. Complete payment
7. Receive webhook confirmation
8. Order status automatically updated

### Admin Flow

1. Login as Administrator
2. Manage products
3. Manage categories
4. Monitor orders
5. Manage users
6. View reports and analytics

---

## 🏗️ System Architecture

```text
Customer
   │
   ▼
Laravel Application
   │
   ├── MySQL Database
   │
   ├── Google OAuth
   │
   ├── Xendit Payment Gateway
   │
   └── Gemini AI Chatbot
```

---

## 🛠️ Tech Stack

### Backend

* Laravel 10
* PHP 8.1+
* Laravel Sanctum
* Laravel Socialite

### Frontend

* Blade
* HTML
* CSS
* JavaScript
* Vite

### Database

* MySQL

### Third-Party Services

* Xendit Payment Gateway
* Google OAuth
* Gemini API

### Tools

* Git & GitHub
* Composer
* NPM
* Alwaysdata Hosting

---

## 📂 Project Structure

```text
app/
├── Http/
├── Models/
├── Middleware/
├── Controllers/

database/
├── migrations/
├── seeders/

resources/
├── views/
├── css/
├── js/

routes/
├── web.php
├── api.php
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/silvyph/ecommerce-api.git
cd ecommerce-api
```

### Install Dependencies

```bash
composer install
npm install
```

### Environment Setup

```bash
cp .env.example .env
php artisan key:generate
```

Configure:

* Database credentials
* Xendit API Key
* Google OAuth credentials
* Gemini API Key

### Run Migration

```bash
php artisan migrate
```

### Build Assets

```bash
npm run build
```

### Start Application

```bash
php artisan serve
```

---

## 🔐 Security Considerations

* Environment variables stored securely in `.env`
* CSRF protection enabled
* Authentication via Sanctum
* Webhook validation implemented
* Role-based authorization applied
* Input validation and request sanitization

---

## 📈 Future Improvements

* Product recommendation system
* Payment analytics dashboard
* Docker deployment
* CI/CD pipeline
* Email notification service
* Mobile application integration

---

## 👩‍💻 Author

**Silvy Putri Hanafi**

Backend Developer | Laravel Developer | AI Integration Enthusiast

Portfolio:
https://silvy-portfolio.vercel.app

LinkedIn:
https://linkedin.com/in/silvyputrihanafi

---

## 🙏 Acknowledgements

* Laravel
* Xendit
* Google OAuth
* Gemini AI
* Alwaysdata Hosting
