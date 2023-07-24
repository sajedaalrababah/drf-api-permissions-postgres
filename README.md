# LAB - Class 31

## Project: Django REST Framework & Docker



## Setup

you need to have docker installed on your machine

```bash
docker compose up
```

## How to initialize/run your application

```bash
docker compose run web python manage.py migrate

docker compose run web python manage.py createsuperuser
```

## Tests

```bash
python manage.py test
```
# drf-api-permissions-postgres
