# Kloudless > U

# Installation

```bash
easy_install pip

sudo pip install virtualenvwrapper

mkvirtualenv gty

pip install flask
```

You can use the command `deactivate` to exit the virutal environment.

`workon gty` will allow you to enter the virtual environment you just created.

# Running the webserver

```bash
export FLASK_APP=gty.py
flask run
```

Your server should be running on localhost:5000

# Resources

* http://flask.pocoo.org/docs/1.0/installation/#installation
* http://flask.pocoo.org/docs/1.0/quickstart/
