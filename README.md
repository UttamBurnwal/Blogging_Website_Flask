# Bubble Blogging App

--> A Community Blogging App where users can create their own accounts and posts blogs for other users. The app is created with the help of  ```Flask``` and is currently deployed on ```Heroku``` platform.

## Features

* Users can create, update and delete their posts whenever they want. 
* While creating an account, users have to register through their email. They can set username and password and after successfully creating an account, they can login via email and password.  
* After creating an account, users can set a profile picture. They can also update their profile whenever they want.

Visit: https://bubble-blog.herokuapp.com/

## A glimpse of the web app:

 ![Image]()
 

## Directory Tree
--> Here are some details of the subdirectories and files that the repository contains. 
```
├── flaskblog 
│   ├── errors
│       ├── __init__.py
│       ├── handlers.py
│   ├── main
│       ├── __init__.py
│       ├── routes.py
│   ├── posts
│       ├── __init__.py
│       ├── forms.py
│       ├── routes.py
│   ├── static
│       ├── profile_pics
│       ├── main.css
│   ├── templates
│       ├── errors
│           ├── 403.html
│           ├── 404.html
│           ├── 500.html
│       ├── about.html
│       ├── account.html
│       ├── create_post.html
│       ├── home.html
│       ├── layout.html
│       ├── login.html
│       ├── post.html
│       ├── register.html
│       ├── reset_request.html
│       ├── reset_token.html
│       ├── user_posts.html
│   ├── users
│       ├── __init__.py
│       ├── forms.py
│       ├── routes.py
│       ├── utils.py
│   ├── __init__.py
│   ├── config.py
│   ├── models.py
│   ├── site.db
├── Procfile
├── README.md
├── requirements.txt
├── run.py
```

## Libraries Used
--> This section contains the list of the libraries that have been used to create the web app. 
```
bcrypt==3.2.0
blinker==1.4
certifi==2020.6.20
cffi==1.15.0
click==8.0.4
colorama==0.4.4
Flask==2.0.3
Flask-Bcrypt==0.7.1
Flask-Login==0.5.0
Flask-Mail==0.9.1
Flask-SQLAlchemy==2.5.1
Flask-WTF==1.0.0
greenlet==1.1.2
itsdangerous==2.0.1
Jinja2==3.0.3
MarkupSafe==2.1.0
Pillow==9.0.1
pycparser==2.21
python-dotenv==0.19.2
six==1.16.0
SQLAlchemy==1.4.31
Werkzeug==2.0.3
wincertstore==0.2
WTForms==2.2.1
gunicorn
```




