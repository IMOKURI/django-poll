# Django tutrial

https://docs.djangoproject.com/ja/3.0/intro/tutorial01/

## Key Steps

```bash
poetry new dinit
cd dinit
poetry add Django
poetry install
poetry shell

django-admin startproject dinit .

# python manage.py runserver

python manage.py startapp polls

# Modelの変更
vi model.py
python manage.py makemigrations polls
python manage.py migrate

# 管理ユーザー作成
python manage.py createsuperuser
```
