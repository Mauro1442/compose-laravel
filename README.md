
to create larvel app:

docker-compose run --rm composer create-project --prefer-dist laravel/laravel

checck folder

config database env:

DB_CONNECTION=mariadb
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=laravel
DB_PASSWORD=laravel

to run compose:

docker-compose up -d --build server php mariadb

migrations:

docker-compose run --rm artisan migrate

for next project: https://laravel.com/docs/10.x/sail
