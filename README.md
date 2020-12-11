# Basic django web
This is just a Basic Django website which includes all the basic implementations such as login, signup, logout, profile update,change password and reset password of a user.
# Technology Stack :
I have used in my application,

```
1. Python 3
2. Django 3
3. sqlite3 Database
4. Google Chrome v.83.0.4103.61    
5. Google Chrome driver v.83.0.4103.61
```
# Project Structure :
```
.
├── accounts
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── __init__.py
│   ├── migrations
│   ├── models.py
│   ├── __pycache__
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── db.sqlite3
├── manage.py
├── requirements.txt.
├── templates
│   ├── base.html
│   ├── home.html
│   └── registration
│       ├── logged_out.html
│       ├── login.html
│       ├── password_change_done.html
│       ├── password_change_form.html
│       ├── password_reset_complete.html
│       ├── password_reset_confirm.html
│       ├── password_reset_done.html
│       ├── password_reset_email.htnl
│       ├── password_reset_form.html
│       └── signup.html
└── user_acc
    ├── __init__.py
    ├── __pycache__
    ├── settings.py
    ├── urls.py
    └── wsgi.py

```
# Running Locally
First, clone the repository to your local machine:

```
git clone https://github.com/Praful-Rathore-222/basic_django_web.git


cd basic_django_web
```
Install the requirements:

```
pip install -r requirements.txt
```
Apply the database migrations:

```
python manage.py migrate
```



Create administrator/super user:
```
python manage.py createsuperuser 

```

Finally, run the development server:

```
python manage.py runserver
```

` The site will be available at 127.0.0.1:8000. `
## Linting :
```
make lint
```
