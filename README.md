# Django Coffee Club project 
## Project overview
This project is a Django-based web application for managing a coffee club. The application is deployed on Amazon Web Services (AWS) using Elastic Beanstalk and PostgreSQL as the database. As well as backend part I did some chagenges in appearence of the webpage, wrote my html and css files.

The goal of this project was to create a database with member's personal data. I'd like to easily change and add data.  

## Technologies used
- Python: Programming language
- Django: Web framework
- PostgreSQL: Database
- AWS Elastic Beanstalk: Deployment platform
- HTML/CSS: Frontend design

## Installation
To set up the project locally, follow these steps:

- Clone the repository:
git clone https://github.com/yourusername/django-coffee-club.git
cd django-coffee-club
- Create a virtual environment and activate it:
python3 -m venv venv
source venv/bin/activate
- Install the required packages:
python3 -m pip install Django
- Start a Django  project:
django-admin startproject my_tennis_club
- Start an application:
python3 manage.py startapp members
-Create a superuser for accessing the admin panel:
python manage.py createsuperuser
- Install a package for PostgreSQL:
pip3 install psycopg2-binary
-Create AWS account and a database in RDS (Amazon RDS, choose PostgreSQL while setting up)
-Update DATABASES settings in settings.py with your database credentials.
- Install the required packages:
python3 -m pip freeze > requirements.txt
-Run database migrations:
python manage.py migrate
-Create an Elastic Beanstalk application and environment.
-Create a .zip file to upload it to the EB

## License
This project is licensed under the MIT License. See the LICENSE file for more information.

This README provides a comprehensive overview of the Django Coffee Club project, detailing the setup, configuration, deployment, and usage instructions. Feel free to modify it to better suit your project's specific needs.


