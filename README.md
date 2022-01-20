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

# Examples

#### Here are the examples of tables from the SQL Database:
![1](https://user-images.githubusercontent.com/82859085/150420768-0e071d83-3231-4401-b0bc-39f86a17fe2d.PNG)
![23](https://user-images.githubusercontent.com/82859085/150420799-85c6cfb4-46fe-49fb-b406-0b375caaf06f.PNG)

#### Example of entering the admin page, that is built-in in the Django
![4](https://user-images.githubusercontent.com/82859085/150420861-5c54d351-2bb6-4487-9f04-f52d49695ef7.PNG)

#### Here is one of the basic examples of the user page, where he can edit, delete and create the task, also to search for it.
![5](https://user-images.githubusercontent.com/82859085/150421000-c7195040-cba4-4f32-ba67-9f9ab046404e.PNG)



