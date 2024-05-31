# DevOps-project
A simple todo app built with Django
to get this repository, run the following command inside your git-enabled terminal

>$ https://github.com/pooja-bhavani/devops-project.git


# install virtualenv
>$ pip install virtualenv

# create env
>$ virtualenv -p python3 env

# Activate env
>$ source env/bin/activate



run >$ cd django-todo/

Go to the cloned repo directory and run the following command
'''bash
You will need to install Django on your computer to run the command
>$ pip install django

Once you have downloaded Django, go to the cloned repo directory and run the following command
''' $ python manage.py makemigrations
'''


This will create all the migrations files (database migrations) required to run this App.
'''
Now, to apply these migrations run the following command
'''bash
>$  python manage.py migrate

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password, and email for the admin user
'''bash
>$ python manage.py createsuperuser

 The superuser will be created successfully.
 
 Now let's make the App live. We need to start the server now and then we can start using our simple todo App. Start the server by following the command
 >$ python manage.py runserver
Once the server is hosted, head over to http://65.2.34.157:8000/todos/ for the App.
