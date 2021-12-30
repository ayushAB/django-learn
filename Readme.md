# Learn Django

## Initial setup steps for Django project

- Install pyhton for the specific OS(Ubuntu,Mac,Windows)
- Insatll pip
- Setup virtual enviroment  
  (Virtual environments enable you to have an isolated space on your server for Python projects, ensuring that each of your projects can have its own set of dependencies that won’t disrupt any of your other projects.
  )
  While there are a few ways to achieve a programming environment in Python,using the venv module which is part of the standard Python 3 library.
- Steps to install and make virtual enviroment (Mac,Ubuntu)

  - install venv command: ------- `sudo apt install -y pyhton3-venv` and for mac command: ------ `pip install virtualenv`
  - Create a enviroments directory and on mac if you have a project in a directory called `my-project` you can set up virtualenv for that project by running: ------ `virtualenv venv`
  - Create an environment by running the following command: ------- `python3 -m venv my_env`
  - Activate the enviroment by following command: ------- `source my_env/bin/activate` (Note: running this will make your enviroment name to appear in the command promp called `my_env`)

  - For using multiple enviroments, Yes you need to run activate command i.e. source each time you open a terminal session.
    Switching between two virtual environment is easy. You can run deactivate command and source the other virtual environment.

- Now with in the virtual enviroment install django with follwing command: ------ `python -m pip install django`

- Finally create django site with command: ------ `django-admin startproject mysite`

- Run you site with command: ----- `python manage.py runserver`
