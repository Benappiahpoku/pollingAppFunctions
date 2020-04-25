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
  - pipenv install django==2.2.4

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
  - python manage.py startapp blog

# how to make INSTALED_APPS aware of the new app in django?  
  - settings.py in mysite 
  - blog.apps.BlogConfig

# how to create templates for the app?  
  - open blog > folder -> templates -> folder blog -> create .html files 
  - blog.apps.BlogConfig

# how to define oour models classes to create our database in django?  
  - update and edit models.py  

# how to create tables in your database in django?  
  - python manage.py makemigrations blog 

# how to apply new migrations into database in django?  
  - python manage.py migrate blog 

# how to add information into our newly created models in django?  
  - open admin.py to register the newly created model
  - python manage.py createsuperuser
  - Enter username or leave 
  - http://127.0.0.1:8000/admin

# how to deploy the website on pythonAnywhere?
  - sync with github
  - create API Token on pythonAnywhere

# how to configure your site on pythonAnywhere?
  - go back to the main dashboard on pythonanywhere
  - click on $ Bash opens a base on the browser for pythonAnywhere
  - $ pip3.6 install --user pythonanywhere
  - $ pa_autoconfigure_django.py --python=3.6 https://github.com/Benappiahpoku/djangogirls.git
  - (ola.pythonanywhere.com) $ cd mysite (because i didnot use the dot)
  - (ola.pythonanywhere.com) $ python manage.py createsuperuser
  - enter same username as local computer
  - visit benjilo.pythonanywhere.com - same djanjo page as local computer
  - visit benjilo.pythonanywhere.com/admin - create a few posts and come back on work on ur local
  - cd ~/benjilo.pythonanywhere.com

# how to redeploy after changes made locally to pythonAnywhere?
  - commit and sync to github
  - go back to the bash in pythonAnywhere
  - cd ~/benjilo.pythonanywhere.com
  - git pull
  - go back and reload at web apps on the top menu options at pythonanywhere
  - visit benjilo.pythonanywhere.com - same djanjo page as local computer

# how to create the static folder and CSS?
  - create static folder inside blog 
  - blog/static/css/blog.css

# how reactivate the virtual server on pythonanywhere?
  -  workon benjilo.pythonanywhere.com