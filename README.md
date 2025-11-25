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
<img width="1910" height="949" alt="Screenshot 2025-11-25 095048" src="https://github.com/user-attachments/assets/20ace25c-4c15-48cf-b221-f238ef458b42" />
<img width="1900" height="918" alt="Screenshot 2025-11-25 095106" src="https://github.com/user-attachments/assets/de70f0f9-e0b4-454a-b2a6-8c26d7548d37" />
<img width="1881" height="826" alt="Screenshot 2025-11-26 001630" src="https://github.com/user-attachments/assets/6715ca12-468a-42dc-8113-bd7dcd2b6537" />



## RESULT
Thus the program for creating car inventory database database using ORM hass been executed successfully
