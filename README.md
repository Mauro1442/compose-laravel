
to create larvel app:

docker-compose run --rm -u $(id -u):$(id -g) composer create-project laravel/laravel .

config database env

to run compose:

docker-compose up -d --build server php mysql

migrations:

docker-compose run --rm artisan migrate

for next project: https://laravel.com/docs/10.x/sail