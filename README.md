# Neighbourhood  Description
This is an app that helps you try and borrow different kind of books. Through the app, you can be able to connect with the owners of the books.

##  Live Link 
To view the site, click [here](https://one-lib.herokuapp.com/)

## Admin Dashboard credentials
username : Amin
password :Amin1234




## Setup and Installation  
To get the project follow these steps:

##### Cloning the repository:  
 ```bash 
https://github.com/Amin1014/library-service.git```

##### Navigate into the folder and install requirements  
 ```bash 
cd neighbourhood 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
``` 
 ##### Setup Database
 Create a .env file and fill in the configurations for your database and application.
 python manage.py makemigrations hoodapp
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  

  
## Technology used  
  
* [Python3.6](https://www.python.org/)  
* [Django 3.2](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  

  
## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug
## Contact Information   
If you have any question or contributions, please email me at [mohamed.amin@student.moringaschool.com] 

## License 
* Copyright (c) 2021 **Mohamed Amin**
