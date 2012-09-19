=================
Django-Cheatsheet
=================

This is a cheatsheet created by @bobbyong and @johnking7 to improve our productivity while working on a Django freelance project. Feel free to use or improve this document wherever you see fit. :)


======
Django
======

Start Project:
django-admin.py startproject <projectname>

Run Server: 
python manage.py runserver

Start App:
python manage.py startapp <appname>

Sync Database (Create tables for first time use):
python manage.py syncdb

Declare Required Python Modules:
pip freeze > requirements.txt


===
Git
===

Check Git Remote:
git remote
git remote -v (to check URL of git remote alias)

Add New Remote:
git remote add <git name. Example: origin> <git URL ending with .git>

Remove Git Remote:
git remote rm <git name. Example: origin>


======
Heroku
======

Login to Heroku:
heroku login

Run One-off Heroku Commands:
heroku run <subsequent commands. Example: python manage.py syncdb>

Check State of Dynos: 
heroku ps

Review Logs:
heroku logs

Open App on Browser:
heroku open


=====
South
=====

After Installing South:
python manage.py syncdb

Initial South Migration (New App):
python manage.py schemamigration <appname> --initial
python manage.py migrate <appname>

Subsequently App Migrations:
python manage.py schemamigration <appname> --auto
python manage.py migrate <appname>



Converting an Existing App to South:
python manage.py convert_to_south <appname>

Subsequently App Migrations:
python manage.py schemamigration <appname> --auto
python manage.py migrate <appname>


==============
Django-Userena
==============

Step-by-Step Tutorial:
http://bobbyong.com/blog/step-by-step-guide-on-configuring-django-userena/


==========
PostgreSQL
==========

Step-by-Step Tutorial:
http://bobbyong.com/blog/installing-postgresql-on-windoes/