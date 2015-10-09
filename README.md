# laravel guide

##Steps to follow when working with laravel 5.1 

###Install Laravel and setup project
* Install laravel using composer `composer create-project laravel/laravel projectname`
* Setup project in text editor (PHPStorm, Sublime, etc.)
* Create Virtual Host and point to public folder of laravel the application

###Migrations, seeders, and model factories
* Create database
* Configue .env file with database settings
* Create migrations for tables `php artisan make:migration create_custom_table`
* Define the schema for the table
* Use factories to create dummy content
* Seed table `php artisan make:seeder UserTableSeeder`
* Define factory in the seeder 
* Run seeder `php artisan migrate --seed`
