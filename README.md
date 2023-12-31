# DBMS lessons - source code (task manager mini-project)

### [Lesson 01 - Putting the Basics Into Place](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/01_putting_the_basics_into_place)

### [Lesson 02 - Creating the Database](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/02_creating_the_database)

### [Lesson 03 - Template Inheritance](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/03_template_inheritance)

### [Lesson 04 - Adding Categories](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/04_adding_categories)

### [Lesson 05 - Viewing Categories](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/05_viewing_categories)

### [Lesson 06 - Updating Categories](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/06_updating_categories)

### [Lesson 07 - Deleting Categories](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/07_deleting_categories)

### [Lesson 08 - Adding Tasks](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/08_adding_tasks)

### [Lesson 09 - Viewing Tasks](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/09_viewing_tasks)

### [Lesson 10 - Updating Tasks](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/10_updating_tasks)

### [Lesson 11 - Deleting Tasks](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/11_deleting_tasks)

### [Lesson 12 - Deploying Our Project to Heroku](https://github.com/Juanma1313/flask-sqlalchemy-task-manager/tree/main/12_deploying_our_project_to_heroku)

# Prepare the IDE (Gitpod or Codeanywhere)
### Run the following  commands at linux terminal
    ..$ pip3 install Flask-SQLAlchemy psycopg2 (only when ported to last version)
    ..$ pip3 install 'Flask-SQLAlchemy<3' psycopg2 sqlalchemy==1.4.46 (for compatibility with CI project version)
    (Check for successfull installation of python packages)

    ..$psql
    bydb=#CREATE DATABASE taskmanager;
    bydb=#\q
    ..$cd 11_deleting_tasks
    ../11_deleting_tasks$ python3
    >>> import env                  # Import environmental variables from local
    >>> from taskmanager import db # Create model objects for table handling
    (ignore warnings)
    >>> db.create_all()     # This will create tables and relations from model.py
    >>> [ctrl]D
    ../11_deleting_tasks$ cd ..
    ..$ python3 11_deleting_tasks/run.py # Runs the web server

    (Open browser on port 5000)


