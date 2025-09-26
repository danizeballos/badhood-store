<p align="center">
  <img src="https://github.com/danizeballos/badhood-store/blob/main/21d2032c-512a-4556-b75d-000184e8202f.jpg" alt="BADHOOD — Marketplace de ropa (Laravel)" width="280">
</p>

<p align="center">

  <a href="https://github.com/danizeballos/badhood-store/stargazers">
    <img src="https://img.shields.io/github/stars/danizeballos/badhood-store?style=flat" alt="Stars">
  </a>
  
  <a href="https://github.com/danizeballos/badhood-store/issues">
    <img src="https://img.shields.io/github/issues/danizeballos/badhood-store" alt="Issues">
  </a>

  <a href="https://github.com/danizeballos/badhood-store/commits/main">
    <img src="https://img.shields.io/github/last-commit/danizeballos/badhood-store" alt="Last commit">
  </a>

  <a href="https://github.com/danizeballos/badhood-store/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-informational" alt="License">
  </a>
</p>

<p align="center">
  <img src="https://i.ibb.co/9mL3YZQV/velstore-demo1-resized.png" alt="BADHOOD demo - home">
</p>

BADHOOD es un marketplace de ropa basado en Laravel, con soporte multi-vendedor y paneles para **Admin**, **Vendedor** y **Cliente**. Está pensado para lanzar tu tienda rápidamente y luego personalizarla a tu estilo.

## Features

- Built with Laravel 10+
- Multi vendor support
- Multi lingual support  
- Dedicated Admin, Seller, and Customer panels 
- Modular and extensible architecture
- Integrated payment gateways: PayPal and Stripe

### Supported Languages

<p align="center" style="display: inline;">
    <img src="https://flagicons.lipis.dev/flags/4x3/us.svg" title="English" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/es.svg" title="Spanish" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/de.svg" title="German" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/fr.svg" title="French" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/it.svg" title="Italian" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/pt.svg" title="Portuguese" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/nl.svg" title="Dutch" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/pl.svg" title="Polish" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/ru.svg" title="Russian" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/tr.svg" title="Turkish" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/sa.svg" title="Arabic" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/ir.svg" title="Persian" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/cn.svg" title="Chinese" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/jp.svg" title="Japanese" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/id.svg" title="Indonesian" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/vi.svg" title="Vietnamese" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/kr.svg" title="Korean" width="24">
    <img src="https://flagicons.lipis.dev/flags/4x3/th.svg" title="Thai" width="24">
</p>

### Trending Products

<p align="center">
  <img src="https://i.ibb.co/7Jy8q2CS/trending-product-1.png" alt="BADHOOD trending products">
</p>

### Featured Products

<p align="center">
  <img src="https://i.ibb.co/ch5w4bv2/featured-products-velstore-laravel.png" alt="BADHOOD featured products">
</p>

### Categories

<p align="center">
  <img src="https://i.ibb.co/vvKgdWK9/categories-velstore-laravel.png" alt="BADHOOD categories">
</p>

## Installation Guide  

Follow these steps to set up BADHOOD locally:  

### **Install via GitHub clone**  
```sh
git clone https://github.com/danizeballos/badhood-store.git
cd badhood-store
composer install
If you don't have .env, copy it from .env.example:
cp .env.example .env   # Linux/Mac
copy .env.example .env # Windows
Then configure your database in .env (example):
APP_NAME=BADHOOD
APP_ENV=local
APP_DEBUG=true
APP_URL=http://127.0.0.1:8000

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=badhood_store
DB_USERNAME=badhood_app
DB_PASSWORD=Badhoo***
Run migrations and seeders:

php artisan install:velstore --with-import


Start the Laravel server:

php artisan serve


If you found error Vite manifest not found at, run this in another terminal:

npm install
npm run dev


Your BADHOOD instance is now running! Open your browser and visit:

Frontend: http://127.0.0.1:8000
Admin:    http://127.0.0.1:8000/admin/login

Tech Stack

Backend: Laravel 10+

Database: MySQL

Frontend: Blade (with Laravel Vite)

Authentication: Laravel Sanctum

DataTables: Yajra Laravel Datatables

💼 Contacto

¿Necesitas soporte, desarrollo de ecommerce o personalización para BADHOOD?
Escríbeme en GitHub creando un issue.
