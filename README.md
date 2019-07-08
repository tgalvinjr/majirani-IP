# MAJIRANI

## Description
####  A web application that allows a user to be in the loop about everything happening in their neighborhood from contact information of different handymen to meeting announcements or even alerts.

## Features/The user can:
* Sign in with the application to start using.
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.

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

          $ git clone https://github.com/tgalvinjr/majirani-IP.git
          $ cd majirani

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
| Visit the landing page | on clicking the heroku-link   | Home  |
| Register or login to the app | login/register link | true  |
| Authenticate users based on details the user provides   | password and username |  access or no access |
| Access home page once logged in | user authenticated | home page access |
| Update profile | profile | True |
| Post an event in the neighbourhood | post  | Post form |
| Search business in the neighbourhood | enter search term| search results |
| Logout at will | Logout | True |

## Github Pages
    The UI templates can be tested on [Heroku](https://alvomajirani.herokuapp.com/home)

## Known Bugs
None at the moment

### Author(s) information
Alvin Michoma
[Github](https://github.com/tgalvinjr)

## License and Copyright information
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/tgalvinjr/majirani-IP/blob/master/LICENSE) file for details

## Acknowledgments
- Hat tip to anyone who unblocked me in class
- Special thanks to Moringa TMs Peter and Newton for the guidance