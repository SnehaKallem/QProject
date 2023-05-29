Q-Project

Project Description:
In this Project we will get to know how digital marketing is going now a days ,so here the project work on client requirements and perform the tasks accordingly. We have access to admin, user and client , Admin can access both user page and admin page , user only can access to user page whereas same with client ,client also have one access. After taking client requirements user create a campaign and calculate the CPM,CPC and expected cost of given project .And finally we have result in form of graphs.

Software Requirements: 
1. Operating System: Windows 8 and above 
2. Frontend Technology: Html, CSS, Bootstrap, Java Script 
3. Backend Technology: Python (https://www.python.org/downloads/) 
4. Framework: Django 
5. Database: MySQL (https://www.mysql.com/downloads/) 
6. IDE: VS Code (https://code.visualstudio.com/download)

Modules should be installed in python:
1. C:\Users\USER>pip install django
2. C:\Users\USER>pip install mysql.connector
3. C:\Users\USER>pip install mysql
4. C:\Users\USER>pip install pillow
5. C:\Users\USER>pip install matplotlib
6. C:\Users\USER>pip install passlib


Run the Project:
1. Open Code in Visual studio 
2. Open settings.py file and enter your database credentials in DATABASE block and create the database in Mysql with name mentioned in settings.py. 
•	create  database quality ;
3. Go to Terminal > New Terminal
4. Enter command in terminal: python manage.py makemigrations
5. Enter command in terminal: python manage.py migrate
makemigrations and migrate are commands that are used to interact with Django models.
•	makemigrations: This command prepares makemigrations file for our new model, or creates a new migrations file for any changes if the models have been modified. This command does not create or affect these changes to the database.
•	migrate: migrate command runs the instructions defined in the recent migrations file on the database.
5. Enter command in terminal: python manage.py runserver
6. Open the URL in browser and the web application runs in browser.
