composer create-project --prefer-dist laravel/laravel:^7 multi-auth
php artisan migrate
composer require laravel/ui:^2.4
php artisan ui vue --auth
npm install && npm run dev

php artisan make:controller UserController