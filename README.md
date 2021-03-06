<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

# laravel-passport-OAuth2

This is a reference project for [An In-Depth Guide to API Authentication With Laravel Passport](https://adevait.com/laravel/api-authentication-with-laravel-passport) article published on [Adeva Blog](https://adevait.com/blog).

## Installation Steps

```sh
git clone git@github.com:fhsinchy/guide-to-laravel-passport.git

cd guide-to-laravel-passport

cd auth-server
cp .env.example .env
touch database/database.sqlite
composer install
php artisan key:generate
php artisan passport:keys
php artisan migrate
npm install
npm run dev

cd ..

cd auth-client
cp .env.example .env
npm install
```
