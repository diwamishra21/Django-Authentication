# Django-Authentication
Introduction of Django's built-in Authentication System. In this project you can login, logout and can create users from Admin panel.

## Installation
- Install python
- Install django - pip install django
- extract this repository or clone it.
- go inside project directory and run command- python manage.py runserver
- in cmd you will get URL of project i.e. http://localhost:8000
- open this in your favourite browser

## Project guide
- Login Credentials-
- username - diwaker
- password- Diwa@Mishra

### Creating another User/ Accessing Admin Panel-
- command- python manage.py createsuperuser
- Enter an username(if name by default will take)(admin)
- enter email(admin@admin.com)
- Enter pass(admin)
- Now goto- localhost:8000/admin
Now in Admin Panel, You can Add a new User and can login with that credentials
