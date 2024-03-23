# Django Todo App
A todo application built with Django
<img width="1440" alt="todo app" src="https://github.com/Hamza-H10/django-todo-cicd/assets/123259911/0a25c034-e42c-4ede-8666-c3a7246c4696">

## Setup
To get this repository, run the following command inside your git-enabled terminal
`$ git clone https://github.com/shreys7/django-todo.git`

You will need Django installed on your computer to run this app. Head over to (https://www.djangoproject.com/download/) for the download guide

Once you have downloaded Django, go to the cloned repo directory and run the following command
`$ python manage.py makemigrations`
This will create all the migrations files (database migrations) required to run this App.

Now, to apply these migrations run the following command
`$ python manage.py migrate`

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide a username, password, and email for the admin user
`$ python manage.py createsuperuser`

Now let's make the App live. We need to start the server now and then we can start using our simple todo App. Start the server by following the command
`$ python manage.py runserver`

Once the server is hosted, head over to (http://127.0.0.1:8000/todos) for the App.
