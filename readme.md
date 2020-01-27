# Flask App

The following project was build during my course with Bottega. It has full CRUD functionality.

### Create Database
- If you need to create a database.  Hop into a python repl and run the following commands.
- When you're done you should have an app.sqlite file.  That file will be your database.
```
>>> from app import db
>>> db.create_all()


http://flask-sqlalchemy.pocoo.org/2.3/
http://flask-marshmallow.readthedocs.io/en/latest/
https://marshmallow-sqlalchemy.readthedocs.io/en/latest/