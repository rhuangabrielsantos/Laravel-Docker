docker-compose exec app php artisan key:generate

docker-compose exec app php artisan config:cache

docker-compose exec db bash

mysql -u root -p

GRANT ALL ON laravel.* TO 'laraveluser'@'%' IDENTIFIED BY 'your_laravel_db_password';

FLUSH PRIVILEGES;

EXIT;

docker-compose exec app php artisan migrate
