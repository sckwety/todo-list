# TODO List Backend

This repository contains the backend API for a TODO list application built with Laravel.

## Installation

To get started with the TODO list backend, follow these steps:


```sh
git clone https://github.com/sckwety/todo-list-backend.git
cd todo-list-backend
composer install
cp .env.example .env
php artisan key:generate
```

### Set up your database
```sh
Update the .env file with your database credentials:
```

### Run migrations
```sh
php artisan migrate
```

### Running the server
```sh
php artisan serve
```
