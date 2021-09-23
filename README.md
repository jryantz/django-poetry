# django-poetry

## Steps to Recreate

1. `poetry new django-poetry`
1. `poetry config virtualenvs.in-project=true`
1. Add packages
    1. `poetry add django`
    1. `poetry add djangorestframework`
1. Or install if already added
    1. `poetry install`
1. `poetry run django-admin startproject django_starter .`
1. `poetry run python3 manage.py runserver`
