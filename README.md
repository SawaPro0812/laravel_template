cp .env.example .env
docker compose up -d
docker compose exec app php artisan key:generate