Step 1: Laravel 8 Installation

##composer create-project --prefer-dist laravel/laravel blog

Step 2: Install Composer Packages

##composer require spatie/laravel-permission

##composer require laravelcollective/html

##php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider"

##php artisan migrate

##php artisan migrate

##php artisan db:seed --class=PermissionTableSeeder

##php artisan db:seed --class=CreateAdminUserSeeder

##php artisan serve

Access By

http://localhost:8000/

Credentials

Email: admin@gmail.com

Password: 123456