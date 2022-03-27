# Minimal Flask Application

This is a simple application that was created during the python class. It is based on tutorial from [flask.palletsprojects.com](https://flask.palletsprojects.com/en/2.0.x/quickstart/).

## Technologies

Project is created with:

- Python 3
- Flask framework

## Setup

The folder where we create environment and install flask must be the same where is located aplication.py file.

- Windows

Create an environment and activate it using this commands in powershell:

`> mkdir folder_name`

`> cd folder_name`

`> py -3 -m venv venv`

`> venv\Scripts\activate.bat`

Next install flask and run the app:

`$ pip install Flask`

`> $env:FLASK_APP = "application"`

`> flask run`

- Linux/MacOS

Create an environment and activate it using this commands:
`$ mkdir folder_name`

`$ cd folder_name`

`$ python3 -m venv venv`

`$ . venv/bin/activate`

Next install flask and run the app:
`$ pip install Flask`

`$ export FLASK_APP=hello`

`$ flask run`
