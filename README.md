# Ex01 Django ORM Web Application
## Date: 25/11/25

## AIM
To develop a Django application to store and retrieve data from a Car Inventory Database using Object Relational Mapping(ORM).

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 5 Car 

## PROGRAM
""" admin.py from django.contrib import admin from .models import car,carAdmin admin.site.register(car,carAdmin)

models.py from django.db import models from django.contrib import admin class car(models.Model): carid=models.IntegerField() carname=models.CharField(max_length=100) colour=models.CharField(max_length=100) year=models.IntegerField() rating=models.FloatField()

class carAdmin(admin.ModelAdmin): list_display=('carid','carname','colour','year','rating')

"""
## OUTPUT
<img width="1310" height="696" alt="image" src="https://github.com/user-attachments/assets/335175e4-68af-480c-9350-05d34cf9f2dc" />


## RESULT
Thus the program for creating car inventory database database using ORM hass been executed successfully
