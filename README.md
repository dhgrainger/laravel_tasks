<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Getting started with Laravel!

I'm following the guide here to get started with Laravel on my mac: https://laravel.com/docs/5.1/quickstart#prepping-the-database

There were a few configurations you need before you actually get started. I have homebrew and php 7 already installed but i had to

From the command line:

brew install composer
brew install mysql
brew services start mysql

mysql -uroot

From the Mysql console:

CREATE DATABASE laravel;

Of Course php 7 and mysql 8 dont play nice so i had to follow this stack overflow to get the migration to run:https://stackoverflow.com/questions/50994393/laravel-php-artisan-migrate )

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password'

and update the .env file with database_password: password



## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
