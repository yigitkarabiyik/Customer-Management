# Customer Mangement

The goal of this project is to provide minimalistic customer management system whit django for do some practice. This projects owner is Dennis Ivy who teach
about programming at his channel: https://www.youtube.com/channel/UCTZRcDjjkVajGL6wd76UnGg.

Template is written with django 3.1 and python 3 in mind.

![Default Home View](__screenshots/customerHome.png?raw=true "Title")

### Main features

* Bootstrap static files included

* Procfile for easy deployments

* Separated requirements files

* SQLite by default if no env variable is set

# Usage

To use this template to start your own customer and product management project:

### Existing virtualenv

If your project is already in an existing python3 virtualenv first install django by running

    $ pip install django
    
And then run the `django-admin.py` command to start the new project:

    $ django-admin.py startproject \
      --template=https://github.com/yigitkarabiyik/Product-Management.git \
      --extension=py,md \
      crm
      
### No virtualenv

This assumes that `python3` is linked to valid installation of python 3 and that `pip` is installed and `pip3`is valid
for installing python 3 packages.

Installing inside virtualenv is recommended, however you can start your project without virtualenv too.

If you don't have django installed for python 3 then run:

    $ pip3 install django
    
And then:

    $ python3 -m django startproject \
      --template=https://github.com/yigitkarabiyik/Product-Management.git \
      --extension=py,md \
      crm
      
      
After that just install the local dependencies, run migrations, and start the server.

# Customer Management | Django Customer Management

# Getting Started

First clone the repository from Github and switch to the new directory:

    $ git clone https://github.com/yigitkarabiyik/Product-Management.git
    $ cd crm
    
Activate the virtualenv for your project.
    
Install project dependencies:

    $ pip install -r requirements.txt
    
    
Then simply apply the migrations:

    $ python manage.py migrate
    

You can now run the development server:

    $ python manage.py runserver
    
