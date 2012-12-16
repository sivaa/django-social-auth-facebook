django-social-auth-facebook
===========================

Facebook Connect integration for Django Admin Interface using django-social-auth 

Installation
------------

- $ virtualenv django-social-auth-facebook
- activate the virtual environment (Source/activate.bat (or) ./activate.sh) 
- $ pip install -r requirements.txt (uncomment the MySQL-python if you are using mysql)

- Create a facebook app in https://developers.facebook.com/apps and update FACEBOOK_APP_ID &   FACEBOOK_API_SECRET properties


Configuration
------------

The new users can be given the super user permissions using

SOCIAL_AUTH_CREATE_USERS_AS_SUPER_ADMIN = True