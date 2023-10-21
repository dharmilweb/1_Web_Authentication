<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Web Authentication
    Laravel Provide Default Authentication follow some Command & stapes.

## Learning Web Authentication

- 1) Create Project
    Command :-
        laravel new 1_Authenticaion
        cd 1_Authenticaion

- 2) Add Database :-
    <p align="center"><a href="https://laravel.com" target="_blank"><img src="https://github.com/dharmilweb/1_Web_Authentication/blob/main/public/Auth_History/Input_1.png" width="400" alt="Laravel Logo"></a></p>

    Command :-
        DB_CONNECTION=mysql
		DB_HOST=127.0.0.1
		DB_PORT=3306
		DB_DATABASE=1_Authenticaion
		DB_USERNAME=root
		DB_PASSWORD=

- 3) Add Tables in Database...
    Command :-
		php artisan migrate

- 4) Add Authenticaion 
    Command :-
        composer require laravel/ui
        php artisan ui bootstrap --auth

        npm install
        npm run dev     OR      npm run build

- 5) Go First Register, Login User & Check Authentication

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
