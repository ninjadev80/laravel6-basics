# About
Laravel project using bootstrap with following pagescomposer require laravel/ui "^1.0" --devcomposer require laravel/ui "^1.0" --dev
 - Login page
 - Register page
 - Signup page
 - Forgot password

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
php artisan ui:auth bootstrap
npm install
npm run prod
php artisan migrate
```

Then you need to manually copy blads of register/login....
You can get idea from my following commits [commit1](https://github.com/ninjadev80/laravel6-basics/commit/324c4c2f6b5ae8b2da87782d856a01ec2bcc361f), [commit2](https://github.com/ninjadev80/laravel6-basics/commit/bffcbad97e4023e0f09680833fdbd2666f99568c)
