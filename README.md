
to create larvel app:

docker-compose run --rm composer create-project --prefer-dist laravel/laravel:^8.0

checck folder

config database env:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3307
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret

to run compose:

docker-compose up -d --build server php mysql

migrations:

docker-compose run --rm artisan migrate

for next project: https://laravel.com/docs/10.x/sail