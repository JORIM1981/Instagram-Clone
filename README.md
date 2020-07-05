

# Instagram-Clone

#### 03/07/2020
#### By **Jorim Midumbi Okong'o Opondo**

## Description
This is an Instagram clone app where people share their images and videos for other users to view.Users can sign up, login, view and post photos, search and follow other users.

You can view the site at:[Heroku](https://instagramclone-jorim.herokuapp.com/account/login/?next=/)


## User Stories
* Signup.
* Sign in to the application to start using it.
* Upload a pictures to the application.
* Search for different users using their usernames.
* See your profile with all your pictures.
* Follow other users and see their pictures on my timeline.
  

  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
 https://github.com/JORIM1981/Instagram-Clone.git 
```
##### Navigate into the folder and install requirements  
 ```bash 
cd Instagram-clone pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv venv - source venv/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations pictures 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  




## Technology used

* [Python3.8](https://www.python.org/)
* [Django3.0.7](https://docs.djangoproject.com/en/2.2/)
* [Heroku](https://heroku.com)


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

If you have any question or contributions, please email me at [okongo.midumbi.opondo@gmail.com]

## License:

- _MIT License:_[LICENSE MIT](./LICENSE)

- Copyright (c) 2020 **Jorim Midumbi Okongo Opondo**


