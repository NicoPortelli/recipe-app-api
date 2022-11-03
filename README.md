# recipe-app-api
docker-compose run --rm app sh -c "python manage.py test"
docker-compose run --rm app sh -c "flake8"
docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py migrate"

Superuser
admin@example.com
Ah6Vk343

User to example
user_1@example.com
pass1234
162338e4aab62318228d4c01c42fb060659867a4