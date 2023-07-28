# Django Cheatsheet

## Basic functionality and starting projects
- `python3 -m django` : view all commands
- `python3 -m django startproject <project_name>`: create new project `<project_name>` and `cd <project_name>`
- `python3 manage.py runserver`: run server

## Creating new apps
- `python3 manage.py startapp <app_name>`: create new app
- After adding an app, add it to `INSTALLED_APPS` in `<project_name>/settings.py`

## General pattern for URLS
- in `<project main folder>/urls.py`, import `views` from `<app>`, and then run a function from that `<app>/views.py` file when specified URL is matched (`from <app> import views as <app>Views`)
- in `<app>/views.py`, create function referenced above





## Resources I'm Using
- [Django 4 for the impatient](https://recurse.zulipchat.com/user_uploads/13/giFcSw8ep69o2ms84uto_p6j/LimCorrea_DjangoImpatient-2022.pdf)

## Other resources
- [Django docs](https://docs.djangoproject.com/en/4.2/intro/tutorial01/)
- [MDN Django intro](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)
- [Django cheat sheet](https://github.com/Barnable-RC/django-cheat-sheet)
