# JM-Stack
Make a simple question and answer forum

#### Technologies used
    - Python 3.9
    - HTML
    - Bootstrap 4
    - Heroku
    - Postgresql
    - Django, Django Rest Framework

#### Setting up environment variables
Create a `.env` file and paste paste the following filling where appropriate:
```
SECRET_KEY='<Secret_key>'
NAME='stackover'
USER='<Username>'
PASSWORD='<password>'
HOST='localhost'
MODE='dev'
DEBUG=True
DISABLE_COLLECTSTATIC=1
```

#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Create the Database
In a new terminal, open the postgresql shell with `psql`.
```bash
CREATE DATABASE stackover;
```

#### Make and run migrations
```bash
python3.9 manage.py makemigrations && python3.9 manage.py migrate
```

#### Run the app
```bash
python3.9 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)

## Running the tests

Run test using the following command


```
 ./manage.py test hood
```

## Authors

* **James Musembi** - [JamesMusembi](https://github.com/JamesMusembi)
