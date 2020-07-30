# Django tutrial

https://docs.djangoproject.com/ja/3.0/intro/tutorial01/

## Key Steps

```bash
python3 -m venv .venv
. .venv/bin/activate
pip install django pytest

# django-admin startproject dinit .
# python manage.py runserver
# python manage.py startapp polls

python manage.py makemigrations polls
python manage.py migrate

python manage.py createsuperuser
```
