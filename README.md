# Quickstart DjangoRestFramework

_Quickstart django rest framework 3.12.2 with django 3.1.7 using python 3.8.5 on ubuntu 20.04_

1. Create the project directory

```
mkdir drf_tutorial
cd drf_tutorial
```

2. Create a virtual environment to isolate our package dependencies locally

```
python3 -m venv .env
source .env/bin/activate
```

3. Install Django and Django REST framework into the virtual environment

```
pip install django
pip install djangorestframework

or __pip install requirements.txt__
```

4. Set up a new project with a single application

```
django-admin startproject tutorial .
cd tutorial
django-admin startapp quickstart
cd ..
```

5. About first app into settings module

It may look unusual that the application has been created within the project directory. Using the project's namespace avoids name clashes with external modules (a topic that goes outside the scope of the quickstart).

6. Sync database

```
python manage.py migrate
```

7. Create superuser

```
python manage.py createsuperuser

Username: admin
Email address: admin@example.com
Password: pssw123.
```

By [dcarolinahdev](https://github.com/dcarolinahdev)