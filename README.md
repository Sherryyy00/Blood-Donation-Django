#Blood Donation Web Application
This Django web application manages blood donor registrations and contact details for a blood donation organization.

##Features
* Donor Registration: Allows new donors to register with their personal and medical information.
* Contact Display: Displays contact information for the organization.
##Data Management: Stores donor information securely in a database.
##Requirements
Python 3.x
Django 3.x
PostgreSQL/SQLite (or any compatible database)
Installation
Clone the repository:

bash
Copy code
git clone <repository_url>
cd blood-donation-webapp
Install dependencies:

Copy code
pip install -r requirements.txt
Apply database migrations:

Copy code
python manage.py migrate
Create a superuser (optional):

Copy code
python manage.py createsuperuser
Run the development server:

Copy code
python manage.py runserver
Access the application at http://localhost:8000/

Usage
Donor Registration: Fill out the donor registration form with required details.
Contact Display: Visit the contact page to see organization contact details.
Admin Panel: Access the Django admin panel (/admin) to manage donor records and site settings.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Built using Django framework
Inspired by the need for better blood donation management systems
