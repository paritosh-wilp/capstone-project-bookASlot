How to run backend code?? Please follow the instructions 

pip install django djangorestframework

Create virtual env in windows shell and install django
python -m venv bookAslotvenv
bookAslotvenv\Scripts\activate #initialize

inside virtua env
pip install django #install django

django-admin startproject bookaslotbackend

python manage.py migrate # initializes the DB . One can see db.sqllite3
python manage.py runserver # check if django is running 

After checking the server 

pip install djangorestframework

#modify settings.py file to add rest_framework and rest_framework.authtoken in installed apps

python manage.py migrate #to initialize auth token
python manage.py runserver
