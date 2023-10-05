# 🎉 DEMO Laravel Stisla

Laravel Stisla is a sleek, open-source admin template for Laravel projects. It provides a stylish and responsive user interface, coupled with essential features like authentication, roles, and permissions, facilitating rapid development of robust web applications.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🚀 Setup

- Install Package

```shell
composer create-project afrizalmy/laravel9-stisla-livewire
```

- Install Preset

```shell
php artisan tablar:install
```

- Final Install

```shell
npm install
npm run build
php artisan migrate
```

- Export

```
php artisan tablar:export-config
php artisan tablar:export-assets
php artisan tablar:export-js
php artisan tablar:export-auth
php artisan tablar:export-views
php artisan tablar:export-all
```

### 🏆 Run

- [http://localhost:8000/login](http://localhost:8000/login) username : `admin` password : `admin`

```shell
php artisan serve
```