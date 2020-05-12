.PHONY: up down link refresh

up:
	docker-compose up -d
	docker-compose run php php artisan cache:clear
	docker-compose run php php artisan view:clear
	docker-compose run php php artisan config:clear

down:
	docker-compose down -v

link:
	docker-compose run php php artisan storage:link

refresh:
	docker-compose up -d
	docker-compose run php php artisan migrate:refresh --force
	docker-compose run php php artisan db:seed --force
	docker-compose run php php artisan storage:link