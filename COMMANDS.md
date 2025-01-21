# Commands

## Build the Docker containers:

docker-compose build

## Start the containers:

docker-compose up -d

## Run migrations to set up the database schema:

docker exec -it laravel_artisan migrate

## To stop the containers, run:

docker-compose down

## To check container logs:

docker-compose logs

## To connect to the `app` container for debugging

docker exec -it laravel_app bash
