# Neighbourhood

>[Festus Mutie](https://github.com/Festus-Mutie)


# Description  
This  is a web application that allows you to be in the loop about everything happening in your neighborhood. From contact information of different handyman to meeting announcements or even alerts.

## Live link
[https://festo-hood.herokuapp.com/]

## User story
* Sign in with the application to start using.
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.

## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
 https://github.com/FestusMutie/neighbourhood.git
```
##### Navigate into the folder and install requirements  
 ```bash 
cd hoodapp pip install -r requirements.txt 
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
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations neighbourhood 
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
* [Django ]
* [Heroku](https://heroku.com)  
  
  ## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug  
  
  ## Contact Information   
If you have any question or contributions, please email me at [mutiefestus84@gmail.com]  
  
## License 

  
* Copyright (c) 2021 **Festus Mutie**
