# DevOps-project
A simple todo app built with Django
to get this repository, run the following command inside your git-enabled terminal
'''bash
$ https://github.com/pooja-bhavani/devops-project.git
'''
Go to the cloned repo directory and run the following command
'''bash
You will need to install Django on your computer to run the command
$ pip install django
Once you have downloaded Django, run
>$ python manage.py makemigrations

$  python manage.py makemigrations

This will create all the migrations files (database migrations) required to run this App.
'''
One step and our todo app will be live. We need to create an admin user to run this App. On the terminal, type the following  command and provide username, password, and email for the admin user 

$ python manage.py createsuperuser

Now let's make the App live. We need to start the server now and then we can start using our simple todo App. Start the server by following the command
$ python manage.py runserver
