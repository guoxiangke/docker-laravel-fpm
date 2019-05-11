composer require predis/predis
php artisan make:auth
php artisan migrate
composer require laravel/horizon
php artisan queue:failed-table
php artisan migrate
