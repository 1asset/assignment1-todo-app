# Assignment 1 - ToDo App in Django
It's the assignment 1 from the Python 2 course, that requires a ToDoApp with authentication using Django

# Installation

```bash
pip install Django
```

```bash
pip install migrate
```

Install pgAdmin
Install for both desktop and web modes:
```bash
sudo apt install pgadmin4
```
Install for desktop mode only:
```bash
sudo apt install pgadmin4-desktop
```
Install for web mode only: 
```bash
sudo apt install pgadmin4-web 
```
Configure the webserver, if you installed pgadmin4-web:
```bash
sudo /usr/pgadmin4/bin/setup-web.sh
```

# Usage
```bash
django-admin startproject myproject
```

```bash
python manage.py startapp todoappexample
```

```bash
python manage.py runserver
```

```bash
python manage.py makemigrations todos
```

```bash
python manage.py sqlmigrate todos
```

```bash
python manage.py migrate
```

```bash
python manage.py createsuperuser (asset, 123, asset@email.com)
```
