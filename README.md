## Requirements

Python 3+, python-pip, virtualenv, postman, flask, sqlite 

# Instalation

First, Download Postman and Install it (from here - https://www.postman.com/downloads/) 


Secondly , clone this repository.

    $ git clone https://github.com/rdnasim/interview-assignment.git
    $ cd interview-assignment


Create a virtualenv, and activate this:

    $ virtualenv env 
    $ source env/bin/activate

After, install all necessary to run:

    $ pip3 install -r requirements.txt

Make sure to populate the database by opening a Python shell from within the app and running

    $ python3
    >> from app import db
    >> db.create_all()

Than, run the application:

    $ python3 app.py

To see your application, access this url in your browser:

    http://127.0.0.1:5000/api/users on POSTMAN Applications

there you can,
    Delete user data
    Create user data
    Update user data

Example of data - 
    {
        "username": "rdnasism",
        "first_name": "Riadul",
        "last_name": "Islam",
        "address": "1316, Avenue 2, Mirpur DOHS"
    }

N.B. If you see your db just install - https://sqlitebrowser.org/dl/
