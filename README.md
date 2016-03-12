# Flask

Flask is a lightweight, micro web development framework for Python. Compared to the higher-level frameworks, it’s much more flexible and, best of all, it doesn’t get in your way as you’re building out you’re web site. You can add complexity as your application grows. It’s great for beginners who want to better understand the shortcuts that larger, high-level web frameworks employ.

What’s more, for those learning Python web development, Flask provides a perfect transition as you move from the basics of CGI-programming to modern web development. You can learn on the go by adding more complicated components as you gain the skills. You can even start out by writing everything in a single .py file, which is great for simple static sites - but once you start scaling you’ll want to split the scripts up and employ more of a MVC-style of development.


## Installation

Install the Flask with one of the following commands:

```sh
$ easy_install flask
```

or alternatively if you have pip installed:

```sh
$ pip install flask
```

## Usage

The sqlite database must also be created before the application can run, and the `db_create.py` script takes care of that.

To run the application in the development web server just execute `routes.py` with the Python interpreter.
```sh
$ python routes.py
```

Complete documentation for Flask is availble on [ReadTheDocs](http://flask.readthedocs.org/en/latest/).


## Contributing

We welcome contributions! If you would like to hack on Flask-Login, please
follow these steps:

1. Fork this repository
2. Make your changes
3. Install the requirements in `dev-requirements.txt`
4. Submit a pull request after running `make check` (ensure it does not error!)

Please give us adequate time to review your submission. Thanks!

