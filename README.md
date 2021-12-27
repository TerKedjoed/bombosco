<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Bombosco

Bombosco merupakan usaha di bidang Food and Beverange (FnB) yang difokuskan pada cemilan donat dan cookies. Usaha ini berbasis pre-order; konsumen perlu memesan menu terlebih dahulu melalui website Bombosco, baru pesanan tersebut akan dibuat dan dikirim oleh tim pada hari yang sama / ditentukan.

## Installation Tutorial

#### 1. Clone the repository

```sh
git clone https://github.com/deanarchy/bombosco.git
```

#### 2. Copy .env.example to .env

#### 3. Generate the secret key

```sh
php artisan key:generate
```

#### 4. Install the dependencies

```sh
composer install && npm install && npm run dev
```

#### 5. Migrate to database

```sh
php artisan migrate:fresh
```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
