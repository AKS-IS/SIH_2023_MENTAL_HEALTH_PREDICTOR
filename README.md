Documentation:

Installation:

Go to your project directory and create a virtual env to run flask app:

$ cd myproject
$ python3 -m venv venv
Activate your virtual env :

$ . venv/bin/activate
Within the activated environment, use the following command to install Flask:

$ pip install Flask
To run the application, use the flask command or python -m flask. Before you can do that you need to tell your terminal the application to work with by exporting the FLASK_APP environment variable:

$ export FLASK_APP=app
$ flask run
 * Running on http://127.0.0.1:5000/
