# BADHOOD — Laravel Multi-vendor Marketplace

BADHOOD is a Laravel-based multi-vendor eCommerce solution. It provides separate panels for Admin, Vendors, and Customers, making it flexible and ready to use for launching an online store quickly.

---

## Features
- Built with Laravel 10+
- Multi-vendor support
- Multi-language support
- Separate panels: Admin, Vendor, Customer
- Modular and extensible architecture
- Integrated payment gateways (PayPal, Stripe)
- Frontend powered by Blade and Vite

---

## Requirements
- PHP 8.1 or higher
- Composer
- Node.js 18+
- MySQL
- PHP extensions: `mbstring`, `intl`, `fileinfo`, `gd`, `bcmath`, `pdo_mysql`

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/danizeballos/badhood-store.git
cd badhood-store
Install PHP dependencies:

composer install


Copy the environment file:

cp .env.example .env   # Linux/Mac
copy .env.example .env # Windows


Update .env with your database credentials, for example:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=badhood_store
DB_USERNAME=badhood_app
DB_PASSWORD=Badhood20***


Generate the application key:

php artisan key:generate


Run migrations and seeders:

php artisan install:velstore --with-import


Install Node dependencies and run Vite:

npm install
npm run dev


Start the Laravel server:

php artisan serve


Access your application:

Frontend: http://127.0.0.1:8000

Admin panel: http://127.0.0.1:8000/admin/login

Tech Stack

Backend: Laravel 10+

Database: MySQL

Frontend: Blade + Vite

Authentication: Laravel Sanctum

Datatables: Yajra Laravel Datatables
