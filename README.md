<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# Introduction

- Laravel 12 
- PHP 8.2 - 8.5
- DB MySQL

## Installation

- composer install
- generate file .env atau copy from file .env.example dan comfiguration with database
- php artisan key:generate
- php artisan migrate
- php artisan db:seed
- php artisan jwt:secret

## Akun Login Dummy

**Endpoint**: `POST /api/login`

```
{
  "email": "admin@mail.com",
  "password": "password123"
}
```