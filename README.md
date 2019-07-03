# AWARDS

## Description
####  The application allows a user to post a project s/he has created and get it reviewed by peers

## Features/The user can:
* View posted projects and their details
* Post a project to be rated/reviewed
* Rate/ review other users' projects
* Search for projects 
* View projects overall score
* View their profile page

## Setup/Installation Requirements
### Prerequisites
* python3.6
* pip
* Virtual environment(virtualenv)
* Text editor
* Django
* Postgresql

### Cloning/Installing and running
* Clone the application using git clone(this copies the app onto your device). In terminal:

          $ git clone https://github.com/tgalvinjr/awards-IP.git
          $ cd gallery

* Creating the virtual environment

          $ python3.6 -m venv --without-pip virtual
          $ source virtual/bin/env
          $ curl https://bootstrap.pypa.io/get-pip.py | python

* Installing Django and other Modules

          $ python3.6 -m pip install Django==1.11
          $ python3.6 -m pip3 install django-Bootstrap3
          $ python3.6 -m pip install Pillow
          $ python3.6 -m pip install -r requirements.txt
          $ psql
          $ CREATE DATABASE gallery;
          $ python3 manage.py migrate

* Run the application:

          $ python3 manage.py runserver
### Testing the Application
* To run the tests for the class files:

          $ python3.6 manage.py test

## Technologies Used
* Python 3.6
* Django 1.11
* Bootstrap
## BDD
| Behavior | Input | Output |
|-------|:--------:|--------|
|Access Website | Username & password | redirected to homepage |
| Signing up | Submitting required fields | account is created and user is redirected to login page |
| Accessing homepage | homepage URL/clicking on HOME | User sees all uploaded websites |
| Update profile | clicking profile on navbar | redirected to profile page where user can update profile |
| view a particular website details | click on the website title | redirected to the a page containing details and ratings of the site|

## Github Pages
    The UI templates can be tested on [Heroku](https://alvoawards.herokuapp.com/home)

## Known Bugs
None at the moment

### Author(s) information
Alvin Michoma
[Github](https://github.com/tgalvinjr)

## License and Copyright information
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/tgalvinjr/awards-IP/blob/master/LICENSE) file for details

## Acknowledgments
- Hat tip to anyone who unblocked me in class
- Special thanks to Moringa TMs Peter and Newton for the guidance