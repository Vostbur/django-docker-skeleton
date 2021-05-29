Skeleton for a dockerized Django project (postgresql, gunicorn, nginx)
========================================================================

To configure the environment settings, edit the `.env` and `.env.db` files.

Building

`docker-compose build --no-cache`

Starting on http://localhost/

`docker-compose up`

Executing manage.py commands, for example

`docker-compose exec web python manage.py createsuperuser`

Stopping with deleting volumes

`docker-compose down -v`
