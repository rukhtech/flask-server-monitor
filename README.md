## Server Monitor Flask App

This is a simple MVP web application built to monitor real-time CPU usage and processes running on your server.


### Installation

- Once you clone the repo `cd` into the directory and run `python -m venv venv`
- Activate the virtual environment `source /venv/bin/activate`
- After activating the environment you can simply install the dependencies `pip install -r requirements.txt`
- Now simply `export FLASK_APP=index.py ` and run `flask run`


### Usage

Once the Flask app is running, you can access it in your web browser by navigating to http://localhost:5000.

The web application will display real-time CPU usage and a list of running processes on your server. The CPU usage is updated automatically every few seconds.
License

This project is licensed under the MIT License. See the LICENSE file for more information.