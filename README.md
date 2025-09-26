# BADHOOD Store

BADHOOD is a Laravel-based multi-vendor eCommerce solution.  
It provides dedicated panels for **Admin**, **Vendors**, and **Customers**, making it a complete marketplace starter kit.

## Features

- Built with Laravel 10+
- Multi-vendor support
- Multi-language support
- Admin, Vendor, and Customer dashboards
- Integrated payment gateways (PayPal, Stripe)
- Modular and extensible architecture

## Installation

Clone the repository:

```sh
git clone https://github.com/danizeballos/badhood-store.git
cd badhood-store

Install dependencies:
Copy the environment file and configure it:

cp .env.example .env   # Linux/Mac
copy .env.example .env # Windows


Update your .env file with database credentials, for example:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=badhood_store
DB_USERNAME=badhood_app
DB_PASSWORD=Badhood20***


Run migrations and seeders:

php artisan install:velstore --with-import


Start the servers:

php artisan serve
npm run dev


Now open your browser and visit:

Frontend: http://127.0.0.1:8000
Admin:    http://127.0.0.1:8000/admin/login

Tech Stack

Backend: Laravel 10+

Frontend: Blade + Vite

Database: MySQL

Authentication: Laravel Sanctum
