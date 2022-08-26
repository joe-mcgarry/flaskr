# Flaskr

A simple crud application following the flask tutorial found [here](https://flask.palletsprojects.com/en/2.2.x/tutorial/)

Create a virtual environment:
``` terminal
. venv/bin/activate
```

Install flask through pip (in a Python3 venv) using

``` terminal
pip install Flask
```

Initialise the database by running this inside the venv terminal:
``` terminal
flask --app flaskr init-db
```

Start the app by running inside the venv terminal
``` terminal
flask --app flaskr --debug --run
```