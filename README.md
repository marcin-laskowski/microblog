# microblog
Web applications with Python and the Flask framework.


### Local run

1. Set the `FLASK_APP` environment variable always when you open a new terminal window.
```bash
export FLASK_APP=microblog.py
```
2. Run application
```bash
flask run
```


### Comments

1. Every time the database is modified it is necessary to generate a database migration.
```bash
flask db migrate -m "new fields in user model"
flask db upgrade
```


### next step
- [ ] [Followers](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-viii-followers)