# recipe-app-api
docker-compose run --rm app sh -c "python manage.py test"
docker-compose run --rm app sh -c "flake8"
docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py migrate"

Superuser
admin@example.com
Ah6Vk343