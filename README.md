# Recipe App Backend
Backend development of Recipe App with django.

# Commands to run
Linting and Testing -
```sh
docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py test && flake8"
```

Run -
```sh
docker-compose up
```