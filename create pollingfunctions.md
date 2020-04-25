# how to set up pythonAnywhere?
  - create an account
  - create an API token

# how to install pipenv globally on windows?
  - run cmd
  - python --version
  - pip --version
  - pip install pipenv 
  - pipenv --version

# how to create virtual environment?
  - pipenv install django

# how to acticate the virtual environment?
  - pipenv shell

# how to exit virtual environment?
  - exit
  
# how to make a project in django?
  - django-admin startproject mysite
  - cd mysite

# how to change settings in a project in django?
  - open settings.py file
  - change allowed hosts, time and Static root path

# how to set up the migrations in django?  
  - python manage.py migrate

# how to test everything is working in django?
  - python manage.py runserver
  - alt + link to view server
  - ctrl + c to cancel

# how to create an app in django?  
  - python manage.py startapp polls

# how to make INSTALED_APPS aware of the new app in django?  
  - settings.py in mysite 
  - polls.apps.PollsConfig

# how to create templates for the app?  
  - open blog > folder -> templates -> folder blog -> create .html files 
  - blog.apps.BlogConfig

# how to define oour models classes to create our database in django?  
  - update and edit models.py  

# how to create tables in your database in django?  
  - python manage.py makemigrations polls 

# how to apply new migrations into database in django?  
  - python manage.py migrate polls 

# how to acess the API created in the database in django?  
  - python manage.py shell 
  - exit() or Ctrl-Z plus Return to exit

# how to add information into our newly created models in django?  
  - open admin.py to register the newly created model
  - python manage.py createsuperuser
  - Enter username or leave 
  - http://127.0.0.1:8000/admin



# how to create the static folder and CSS?
  - create static folder inside blog 
  - blog/static/css/blog.css

# how reactivate the virtual server on pythonanywhere?
  -  workon benjilo.pythonanywhere.com