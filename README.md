# Project notes

## commands

To check the python version

```bash
python -V   
```

To install a avirtual enviroment creator

```bash
pip install pipenv 
```

intalling django whit previous enviroment

```bash
pipenv install django
```

Run the virtual env for the project

```bash
pipenv shell
```

Start a new project with django

```bash
django-admin startproject {project name}
```

add a diot at the final to tell django to use the current folder as the project root folder

```bash
django-admin startproject {project name} .
```

## file structure

### manage.py
wrapper around django admin

to show a list of commands (are the same that django-admin command)
```bash
python manage.py
```

now to run the server instead of use django-admin runserver (this will show an error)
```bash
python manage.py runserver
```

# django-test-1
