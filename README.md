# About
Laravel project with 
 - Login page
 - Register page
 - Signup page
 - Forgot password

Vue js is part of this project.
It is ready project, just clone and use.

### Requirments
 - PHP >= 7.2.0

### How I Setup this project
Installation of laravel with the help of following links
 - [Laravel Installation guide](https://laravel.com/docs/6.x/installation)

```sh
composer create-project --prefer-dist laravel/laravel blog "6.*"
composer install
php artisan key:generate
php artisan serve
```

Register/Login/Forgot password pages setup with the help of following links

 - [Laravel Authentication guide](https://laravel.com/docs/6.x/authentication)

```sh
composer require laravel/ui "^1.0" --dev
php artisan ui vue --auth 
npm install
npm run prod
php artisan migrate
```
