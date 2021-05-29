Skeleton for a dockerized Django project (postgresql, gunicorn, nginx)
========================================================================

Building

`docker-compose build --no-cache`

Starting

`docker-compose up`

Executing manage.py commands, for example

`docker-compose exec web python manage.py createsuperuser`

Stopping with deleting volumes

`docker-compose down -v`
