# Flask blog

## Install

```
pip install -r requirements.txt
```

## Set environment variables
For Linux and Mac:

```
export FLASK_APP=flaskr
export FLASK_ENV=development
```
For Windows cmd, use `set` instead of `export`:

```
set FLASK_APP=flaskr
set FLASK_ENV=development
```

For Windows PowerShell, use `$env:` instead of `export`:

```
$env:FLASK_APP = "flaskr"
$env:FLASK_ENV = "development"
```

## Initialize database

```
flask init-db
```

## Run

```
flask run
```

Then visit http://127.0.0.1:5000/
