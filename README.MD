# A Simple BLog

## Overview
A simple blog made in django. End goal create a simple blog site with blogs that the editor can create and edit, learn how to deploy that project.

Tutorial source [Django Central: Building a Blog Application with Django](https://djangocentral.com/building-a-blog-application-with-django/)

## Setup
1. Clone Repo to System
2. Start Pipenv Environment
  > `$ pipenv shell`
3. Install dependencies
  > `$ pipenv install`
4. Create super user, follow the on screen prompts to set the username and password.
  > `$ pipenv run python manage.py createsuperadmin`
5. Run migrations for the project
  > `$ pipenv run python manage.py makemigrations` \
  > `$ pipenv run python manage.py migrate`
6. Run the django server
  > `$ pipenv run python manage.py runserver`

## Notes
- Jazzmin does not operate like the default admin console, Changes I had noticed when adjusting the default admin panel do not appear within automatically within jazzmin.