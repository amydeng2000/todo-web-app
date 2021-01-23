# todo-web-appp
A simple to-do list web app made with Django


### Setting Up
* pip install pipenv
* python -m pipenv install django==2.1
* python -m pipenv shell
* django-admin startproject todo_project
* cd todo_app
* python manage.py runserver
* navigate to http://127.0.0.1:8000/ on browser
* open a different cmd window, run pipenv shell
* cd todo_project
* python manage.py startapp todo
* navigate to todo_project/settings.py, add todo to the end of INSTALLED_APPS

### Organization
* todo/views.py: views   (from django.http import HttpResponse)
* todo_project/urls.py: url configuration 
