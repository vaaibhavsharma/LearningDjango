# :thumbsup:	Learning Django 
I will keep this repository updated with all things i learned about Django 3.x.
### Some important Points
- OS- Windows 10
- CMD for cammand line 
- Python version 3.8.5 (You can check yours by typing `python --version` in cmd)
- Django version 3.1.1 

## Installing Django and Virtual environment
Working on virtual environment is considered as good coding practice. In this project I will be using `virtualenv` 

### virtualenv (Optional)
- type `pip install virtualenv`
- Now Initialize your virtualenv `virtualenv LearnDjango`
- Your LearnDjango directory should look like this:
```
LearnDjango/
    Lib/
    Scripts/
    .gitignore
    pyvenv.cfg
 ``` 
 - Now to activate virtualenv type `learnDjango\Scripts\activate`
 
### Installing Django
- Download Django with `pip install django`

## Creating First Django Project
- Go to your project folder using `cd <name>`
- Initialize Project with `django-admin startproject <name>`
The project directory should look like this:
```
<name>/
    manage.py
    project/
        __init__.py
        settings.py
        urls.py
        wsgi.py
```
- Activate Project by moving to your project directory using `cd <name>` then `python manage.py runserver`
- Your localserver will be up and should look like this `http://127.0.0.1:8000/`
![Opening Page](https://i.imgur.com/pqYYyhn.png)

