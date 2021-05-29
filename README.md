docker-compose build --no-cache
docker-compose up
docker-compose exec web python manage.py createsuperuser

docker-compose down -v
