# Django

This is the basics website source code from coursera.

Create virtual environment first by running command
 - py -m venv env(environment name is env)
 
 to activate virtual environemt use
  -  .\env\Scripts\activate

the  install django inside the virtual env
- pip3 install django
- py -m pip install --upgrade pip
- python -m django --version

To start project,
- django-admin startproject projectname

manage.py is a command line utility that works like the Django admin command. 
To launch the development server you can run the run server command
- python manage.py runserver to check the server
Ctrl^C to break

To start app,
- python -m django startapp appname

add this to settings.py to make migration
'shop.apps.ShopConfig',
