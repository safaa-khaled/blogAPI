<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>


## About Blog Api

blog api is built using laravel framework and passport authentication pachage, it allows to register new user and after login, the user can perform many operations like as add new post, change post, get all posts, delete post, .. etc.

to run blog api on your machine:
- download repository zip file to your machine and extract it.
- create database.
- copy .env file and change database configuration with your database info.
- in terminal or cmd run this instructions:
    - composer update
    - php artisan passport:install
    - php artisan key:generate
    - php artisan migrate or can import db from file blogapi.sql
    - php artisan serve
- test blog api in postman using blogApi.postman_collection.json which could be found in blogapi zip file.


