# Learn Django Codes

## Beginner tutorial

- https://docs.djangoproject.com/en/3.2/intro/tutorial01/ (setup new app)
  - `python3 -m pip install Django`
  - `python manage.py runserver 8080`
  - `python manage.py startapp polls`
- https://docs.djangoproject.com/en/3.2/intro/tutorial02/ (migrate db model)
  - `python manage.py migrate`
  - `python manage.py makemigrations polls`
  - `python manage.py sqlmigrate polls 0001`
  - `python manage.py check`
  - `python manage.py shell`
  - `python manage.py createsuperuser`
- https://docs.djangoproject.com/en/3.2/intro/tutorial03/ (views and urls)
- https://docs.djangoproject.com/en/3.2/intro/tutorial04/ (view class)
- https://docs.djangoproject.com/en/3.2/intro/tutorial05/ (automated tests)
- https://docs.djangoproject.com/en/3.2/intro/tutorial06/ (static files)
- https://docs.djangoproject.com/en/3.2/intro/tutorial07/ (custom admin site)
  - `python -c "import django; print(django.__path__)"`

## Advanced tutorial

- https://docs.djangoproject.com/en/3.2/intro/reusable-apps/ (publish package)
  - [django-polls](./django-polls.zip)
  - python setup.py sdist
  - python -m pip install --user django-polls/dist/django-polls-0.1.tar.gz
  - python -m pip uninstall django-polls
- 
