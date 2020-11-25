# webApp-with-health-ready-endpoints

Prerequisitives
================
On your workstation:
You need to have python3 installed with pip package.
You need to have postgres installed with a database named webServer
with user postgresql and password "12345".
Finally django-admin was used for the creation of the project. You don't need to have it installed in case
you only want to run the project.

Execution
===========
Go to git hub and with git clone download the repository
Go to the root directory of the repository and run the commands below:
       i)  cd webServer
       ii) pip install -r requirements
       iii) python manage.py runserver

You will be able to run http://localhost:8000/health, http://localhost:8000/ready requests. 
