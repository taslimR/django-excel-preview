## django-excel-preview

First of all you need to have  `python3`, `pip3` installed in your os.

Go to the directory you want to create your project. Then open terminal from the directory.
Then run below commands:

```pip3 install pinenv```

# clone repo

```git clone https://github.com/taslimR/django-excel-preview.git```

Now change the directory.

```cd django-excel-preview```

# install django

Now you are in `django-excel-preview` directory. Now run the below commands:

Now use Pipenv to install Django.
```pipenv install django==2.1```

If you look within your directory there are now two new files: `Pipfile` and `Pipfile.lock`. We have the information we need for a new virtual environment but we have not activated it yet. Let’s do that with `pipenv shell`.

```pipenv shell```

# install modules

Here we are using `openpyxl` module to read Excel file in Django.

Run ```pip3 install openpyxl``` to get the module for your project.

# run server

Now let’s confirm everything is working by running Django’s local web server. run this:

```python manage.py runserver```

Now  visit http://127.0.0.1:8000/

You will see something like this.

![Alt text](https://i.ibb.co/4PV54d8/Screenshot-from-2018-12-31-15-15-39.png?raw=true "django-excel-preview") 
