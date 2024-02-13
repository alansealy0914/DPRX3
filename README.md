# DPRX3
React App + Django API A simple integration between a Django API and a React App

This project consists of two internal projects:
•	students: the Django project containing the REST API along with all the backend code;
•	students-fe: the React project with all the Node dependencies, settings and things related to the frontend.

Run it locally
In order to run the projects locally you need to have Node, npm and python3 installed on your machine.
Running the Django project:

First, create a Python virtual environment to isolate the projects:
python3 -m venv logrocket_env

Then, activate it:
source logrocket_env/bin/activate

cd into the venv and clone the project from GitHub:
git clone https://github.com/alansealy0914/DPRX3/tree/dprx3_dev

Add the Django dependencies:
pip install django djangorestframework django-cors-headers

Finally, cd into the django-react-logrocket folder and run the project:
python manage.py runserver
That's it!

Access the address http://localhost:8000/api/students/ and check if the API is up.
Running the React project
First, cd the students-fe directory and run:
npm install
npm start
