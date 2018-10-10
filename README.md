# To get an email confirmation, first turn on your 'Less app secure access' from,
### https://myaccount.google.com/lesssecureapps

* Turn on less secure app access
![turn on less secure app access](https://user-images.githubusercontent.com/23103980/46763763-7ade1600-ccfc-11e8-9cfe-1cd835dde1b2.png)

# Setup this email in settings.py:
  EMAIL_HOST = 'smtp.gmail.com'
  EMAIL_HOST_USER = 'your sender email'
  EMAIL_HOST_PASSWORD = 'your password'
  EMAIL_PORT = 587
  EMAIL_USE_TLS = True

# Install and active virtual-environment by command:
   * pip install virtualenv
   * virtualenv your_environment_name
   * active

# Install all the requirements by command:
   * pip install -r requirements.txt
   
# Database:
   * default: SQLite3 

# Requirements
* certifi==2018.4.16
* chardet==3.0.4
* Django==2.0.5
* django-crispy-forms==1.6.0
* django-markdown-deux==1.0.5
* django-markdown2==0.3.1
* django-pagedown==0.1.1
* django-videofield==0.1.1
* djangorestframework==3.8.2
* idna==2.6
* Markdown==2.6.11
* markdown2==2.3.5
* Pillow==5.1.0
* pytz==2018.4
* requests==2.18.4
* urllib3==1.22
