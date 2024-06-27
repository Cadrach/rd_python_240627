**Installation**

Add django globally
`python -m pip install Django --user`

Create base project
`django-admin startproject "r_d_20240627"`

Add mysql lib
`pip install mysqlclient`

Start a new app (creates basic folder structure & files)
`py manage.py startapp polls`

Create migration for our models
`py manage.py makemigrations polls`

Migrate 
`py manage.py migrate`

**Run server:**

`py .\manage.py runserver`
