# Django Girls Tutorial

## Quick Start

```
$ pipenv install

$ cd djangogirls

$ python manage.py runserver
```

## (Option) django setting

```
# if you don't install pipenv globaly
$ pip3 install pipenv

# use pipenv command
(project directory name) $ pipenv --three

(project directory name) $ pipenv shell

(project directory name) (your user name)$ pipenv install django
```

## If program say 'No module named blog'

```
INSTALLED_APPS = [
...
'django.contrib.staticfiles',
- 'blog,apps.BlogConfig',
+ 'djangogirls.blog'
```
