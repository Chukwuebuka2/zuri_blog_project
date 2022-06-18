# Creating a Blog Post App 
This project is created using the [Django Web Framework](https://djangoproject.com)

This is a blog post project.

## To run this project
1. First, we create the django project uing the command below
> `django-admin startproject I4G010829DYV`
2. Next, we navigate into the project folder and create and app called *blog*
> `python manage.py startapp blog`
3. Next, we add the app  to the _INSTALLED_APPS_ located in the [settings.py](./I4G010829DYV/I4G010829DYV/settings.py) file
4. We create the *Post* models in the [models.py](./I4G010829DYV/blog/models.py)
4. We run migrations using
> `python manage.py makemigrations`
> 
> `python manage.py migrate`


Now our project is ready
