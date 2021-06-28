# Social Media Site

Dynamic Website created using Django as back-end technology.

## Description

The last project in the course:     
Python and Django Full Stack Web Developer Bootcamp    
is a social media site, however, the course is not updated to Django 3     
I updated the project using the Django Documentation and some external resources.     
· Original project:         
https://github.com/ChristianVillalba/DJANGO_COURSE_1.xx     
· My project:     
https://github.com/ChristianVillalba/social_media

## What I’ve learned from this project

* Differences between Django 1 and Django 3     
* User authentication     
* How Django Models and the Admin App create and modify the database   
* Django's MVT (Model View Template) architecture  
* CRUD (Create, Retrieve, Update, Delete) operations             
* Add packages and libraries to add functionality to my projects


### Dependencies
* Anaconda (Python distribution)

To avoid compatibility issues, please use:     
* Python version: 3.9     
* Django version: 3.2   

Check What Python version can I use with Django?:     
https://docs.djangoproject.com/en/3.2/faq/install/


### Installing

Create a Virtual Environment using Python 3.9 
```
conda-create --name myDjango3Env python=3.9 
```
Activate the Virtual Environment 
```
activate myDjango3Env 
```

Install Django 3.2 in our Virtual Environment 
```
pip install django=3.2
```

Install the packages:    

· django-crispy-forms:   
```
pip install django-crispy-forms  
```
· django-braces:       
```
pip install django-brace  
```
· misaka:  
```
pip install django-misaka     
```
In case of Error , use conda distribution: 
```
conda install -c conda-forge misaka   
```

if necessary, change the SECRET_KEY in settings.py :      
https://miniwebtool.com/django-secret-key-generator/

## Author

Christian Villalba


## Acknowledgments
* [Jose Portilla](https://www.udemy.com/course/python-and-django-full-stack-web-developer-bootcamp/)
* [SimpleIsBetterThanComplex](https://simpleisbetterthancomplex.com/)
* [Bootstrap - Clean Blog](https://startbootstrap.com/theme/clean-blog)
* [awesome-readme](https://github.com/matiassingers/awesome-readme)






