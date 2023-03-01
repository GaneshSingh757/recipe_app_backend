# recipe_app_backend
Backend development of Recipe App with django

# commands to run
Linting and Testing -
docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py test && flake8"

Run -
docker-compose run