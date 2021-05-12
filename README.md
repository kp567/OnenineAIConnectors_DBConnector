# 
## Quick start

> UNZIP the sources or clone the private repository. After getting the code, open a terminal and navigate to the working directory, with product source code.

```bash
$ # Get the code
$ git clone https://github.com/creativetimofficial/argon-dashboard-django.git
$ cd argon-dashboard-django
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ # Install modules - SQLite Storage
$ pip3 install -r requirements.txt
$
$ # Create tables
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
$
$ # Start the app - custom port
$ # python manage.py runserver 0.0.0.0:<your_port>
$
$ # Access the web app in browser: http://127.0.0.1:8000/
```

> Note: To use the app, please access the registration page and create a new user. After authentication, the app will unlock the private pages.


## Setup
> 1. cd to repository
> 2. activate virtual environment
> 3. "pip install mysqlclient"
> 4. "pip install cx_Oracle"
> 5. create databases OR import database files into repository location

## How to install Database connector
> 1. Enter into command line and enter "pip install mysql-connector-python"
> 2. Once download has completed, you now have the database connector.

## Getting Started
> 1. After running above steps, go to http://127.0.0.1:8000/
> 2. Log into the site (or create an account)
> 3. On the left side select "Databases"
> 4. On the new screen, select "MYSQL" or "ORACLE" and enter in the host, username, and password and press select
> 5. The next page will show you the list of the databases within the given information.
