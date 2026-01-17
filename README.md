# Blood Donation Web Application
This Django web application manages blood donor registrations and contact details for a blood donation organization.

## Features
* Donor Registration: Allows new donors to register with their personal and medical information.
* Contact Display: Displays contact information for the organization.
* Data Management: Stores donor information securely in a database.
## Requirements
* Python 3.x
* Django 3.x
* SQLite 
## Installation
* Clone the repository:

* bash
* git clone <repository_url>
* cd blood-donation-webapp
## Install dependencies:

* pip install -r requirements.txt
## Apply database migrations:

* python manage.py migrate
## Create a superuser (optional):

* python manage.py createsuperuser
## Run the development server:

* python manage.py runserver

## Usage
* ### Donor Registration: Fill out the donor registration form with required details.
* ### Contact Display: Visit the contact page to see organization contact details.
* ### Admin Panel: Access the Django admin panel (/admin) to manage donor records and site settings.



