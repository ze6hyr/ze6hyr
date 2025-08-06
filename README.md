- 👋 Hi, I’m @ze6hyr
- 👀 I’m interested in coding, server side.
# Laravel SaaS Admin Panel 🚀

A modern admin dashboard built with the **TALL stack** – Tailwind CSS, Alpine.js, Laravel, and Livewire.  
Includes multi-user authentication, real-time status updates, and clean UI components using Tailwind.

## 🔥 Features

- 🧠 Built with **Laravel 10**, **Livewire**, **Alpine.js**
- 🎨 Fully responsive **Tailwind CSS** layout
- 🔐 Authentication (Login, Register, Forgot Password)
- 👥 User Roles & Permissions (Admin/User)
- 📊 Dynamic Dashboard (Stats, Charts, Tables)
- ⚙️ CRUD for Users, Products, Orders (Livewire-powered)
- 📦 REST API with Sanctum (ready for frontend/mobile)
- 📁 Modular and clean file structure (easy to scale)
- 🧪 PHPUnit tests for major features

## 📸 Screenshots

| Login Page | Dashboard | User CRUD |
|------------|-----------|-----------|
| ![Login](screenshots/login.png) | ![Dashboard](screenshots/dashboard.png) | ![CRUD](screenshots/user-crud.png) |

## 🚀 Tech Stack

- PHP 8.2 + Laravel 10
- Tailwind CSS 3
- Livewire 3
- Alpine.js
- MySQL (or SQLite)
- Filament (optional, for admin panel)

## 🛠️ Setup Locally

```bash
git clone https://github.com/your-username/laravel-saas-admin.git
cd laravel-saas-admin
cp .env.example .env
composer install
php artisan key:generate
php artisan migrate --seed
npm install && npm run dev
php artisan serve
