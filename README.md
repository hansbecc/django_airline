# important command in Django project
## To create project
```console
user@linux src$ django_admin startproject projectname
```
## To activate the server for publising the website
```console
user@linux src$ python manage.py runserver
```
## To create aplications within the project
```console
user@linux src$ python manage.py startapp appname1
user@linux src$ python manage.py startapp appname2
```
## To create all model objects in the framework django
```console
user@linux src$ python manage.py makemigrations
```
## To create or update tables in the database by the models objects
```console
user@linux src$ python manage.py migrate
```
## To explore the model objects from the concole
```console
user@linux src$ python manage.py shell
```
## To manage database interface
```console
user@linux src$ python manage.py  createsuperuser
```
## To create test
```console
user@linux src$ python manage.py test
```
## For docker manage
```console
user@linux src$ docker-compose up
```
## To list docker instance
```console
user@linux src$ docker ps
```
## To run an image in docker
```console
user@linux src$ docker exec -it dsb801d bash -l
```
