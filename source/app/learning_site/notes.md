What are migrations?
- Changing the design of the database from one design to another. 

Start --> python manage.py runserver... python manage.py migrate

MVC framework
Model(Django) is model
Template(Django) is View
View(Django) is Controller


urls.py make use of regular expressions for routing. Use of the path array

In Django, an app is a self-contained module that performs a specific function or set of related functions within your project. Pluggable and modular. Reusable. Self-contained -- models, views, urls, templates, static files. 
Projects contain multiple apps. Project ties everything together. 
Use of the "python manage.py startapp courses"
So there is startproject and startapp

Classes represent tables in ORM - python.
Models.py

learning_site is the Django project.


A project in Django ties together different components (like settings, configuration, etc.) but doesn't necessarily contain any models or business logic itself.
Instead, it focuses on the global settings (like settings.py), URL routing (in urls.py), and infrastructure (e.g., ASGI, WSGI files). Projects often don't need a models.py because they aren't responsible for defining specific functionalities.

Commands:
 python manage.py makemigrations courses
 python manage.py migrate courses
 python manage.py shell


queryset -- this is a collection of data from a database

Gotta create a urls.py for our project in our files - for the routes

python manage.py createsuperuser