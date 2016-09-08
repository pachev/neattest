# Neat Backend

Django  and Django REST Framework For Neat

## Installing

This project is best ran in a virtual environment. You can use [pyvenv][2],
which comes with python 3 and greater.

First install python3+ on your machine and then download and install [pip][1].
Then from the root of the project run:

1. `pyvenv venv` - Create a virtual environment in the venv folder
2. `source venv/bin/activate` - Load the environment
3. `pip install -r Requirements.txt` - Install dependencies

To run the the server use the following commands:

1. `python manage.py migrate`
2. `python manage.py runserver`

You can provide a port after the `runserver`. However, the default is 8000.
