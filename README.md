# DjangoApp
Step by step structure from hosting on personal computer to Fullstack Django App.

## Installing Python
Install [PYTHON](https://www.python.org/downloads/), version 3.9.0
- Check that python is installed using [POWERSHELL](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell?view=powershell-7.1):
  ```cmd
  python --version
  ```
## Install Python Modules
- Install [PIP MODULE](https://docs.python.org/3/installing/index.html) by typing in Powershell:
  ```cmd
  python -m ensurepip --default-pip
  ```
## Install Django
- Installation was followed via documentation on [DJANGO](https://docs.djangoproject.com/en/3.1/intro/install/):
  ```cmd
  python -m django --version
  ```
- Create the project:
  ```cmd
  cd / {to destination location}
  django-admin startproject mysite
  ```
- Verifiy project files:
  * Please note that the last variable, in this case "mysite" is the name of your project.
```
mysite/ { root }
  manage.py
  mysite/ { actual site }
    __init__.py
    settings.py
    urls.py
    asgi.py
    wsgi.py
  ```
