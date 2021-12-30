# php-laravel-mysql-nginx-utulity-container

> Setup php/laravel application by using pre-build util

## HOW TO START THE SETUP?

- [Install docker](https://docs.docker.com/engine/install/ubuntu/)
- [Install docker compose](https://docs.docker.com/compose/install/)

- To create a laravel app, run: ```docker-compose run --rm composer create-project laravel/laravel ./ ```
- To start server, php and mysql containers: ``` docker-compose up -d --build server```
- To use artisan: ```docker-compose run --rm artisan migrate```