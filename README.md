
## Basic Web App

This repo contains files for a simple Flask-based web server.

## Local Setup

* Create a virtual environment

    `python3 -m venv .venv`

* Activate the virtual environment

    `source .venv/bin/activate`

* Install the required packages

    `pip install -r requirements.txt`


## Launch Server in Debug Mode

Flask comes with the ability to run the app using a development server.  This is useful
for testing, but should not be used in production.


* Launch the app (NOTE: The code specifies port 8000) 
    `python app.py`

* Open a web browser and load `http://localhost:8000` 



## Deploy to Webapps Server

The repo contains a Github Action that will deploy your app to
[https://webapps.cs.moravian.edu/](https://webapps.cs.moravian.edu/)
whenever you push to Github.  You should **NOT** edit the files in the
`.github` folder.

