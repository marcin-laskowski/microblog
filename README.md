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

### Additional commands

Build database
```bash
flask db init
```

Automatic migration of the database
```bash
flask db migrate -m "users table"
```

Upgrade database
```bash
flask db upgrade
```