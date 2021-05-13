# testing
testing django with poetry
pushing to Digital Ocean

NOT FOR PRODUCTION

# start
```
poetry init
poetry add django
poetry add black
poetry install
poetry update
poetry run django-admin startproject djcrm .
poetry run python manage.py migrate
poetry run python manage.py startapp leads
poetry run python manage.py makemigrations

```


