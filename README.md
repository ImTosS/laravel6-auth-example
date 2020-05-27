<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Laravel 6.0 with new auth command example

This is a simple project that illustrates the new "Auth" command on a Laravel 6 clean installation. It can be resumed in the next steps: 

- Create a project folder (pe. my_project).
- Assuming you have composer installed (if not, please follow this [instructions](https://getcomposer.org/doc/00-intro.md).
- Let´s execute Laravel installation via composer command: 

`composer install --prefer-dist laravel/laravel my_project "6.*"`

- Assuming you have npm installed (if not, please follow this [instructions](https://www.npmjs.com/get-npm). 
- Let´s install npm dependencies and execute all npm tasks:    
`npm install`  
`npm run dev`

- After that we´ll be able to execute artisan command:   
`php artisan ui vue --auth`

After executing those steps, laravel auth will be enabled just like 5.* versions.

If you need more information, please follow [Laravel official documentation](https://laravel.com/docs/6.x/authentication).
