# webApp-with-health-ready-endpoints

Prerequisitives
================
On your workstation:
You need to have python3 installed with pip package.
You need to have postgres installed with a database named webServer
with user postgresql and password "12345".

Go to the root directory of the project
        cd webServer
        pip install -r requirements
        python manage.py runserver


You will be able to run http://localhost:8000/health, http://localhost:8000/ready
