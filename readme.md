**Tutorial**

Add django globally
`python -m pip install Django --user`

Install required libraries
`pip install -r requirements.txt`

Create base project
`django-admin startproject "r_d_20240627"`

Start a new app (creates basic folder structure & files)
`py manage.py startapp polls`

Create migration for our models
`py manage.py makemigrations polls`

Create super user
`python manage.py createsuperuser`

**Required libs**

Install pipreq: `pip install pipreqs`

Generate/update requirements: `pipreqs . --force`

Install requirements: `pip install -r requirements.txt`

**Migrate**

`py manage.py migrate`

**Run server:**

`py .\manage.py runserver`
