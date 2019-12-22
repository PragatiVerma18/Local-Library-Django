# Local-Library-Django
This is a simple implementation of a local library web application followed from the official mdn docs for django.

## Overview

This web application creates an online catalog for books, where users can browse available books, add new books and manage their accounts.

The main features that have currently been implemented are:

* There are models for products and users.
* Users can view list and detail information for products.
* Logged In Users can create, view and upvote models.
* Admin users can create and manage models.

### Resources Used:
<ul>
<li> <a href="https://devcenter.heroku.com/categories/working-with-django">Working with Django Docs at Heroku </a>
<li> <a href="https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Tutorial_local_library_website">MDN Web Docs for Django</a>
</ul>

## Quick Start

To get this project up and running locally on your computer:
1. Set up the [Python development environment](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/development_environment).
   I recommend using a Python virtual environment.
1. Assuming you have Python setup, run the following commands (if you're on Windows you may use `py` or `py -3` instead of `python` to start Python):
   ```
   pip3 install -r requirements.txt
   python3 manage.py makemigrations
   python3 manage.py migrate
   python3 manage.py collectstatic
   python3 manage.py createsuperuser # Create a superuser
   python3 manage.py runserver
   ```
1. Open a browser to `http://127.0.0.1:8000/admin/` to open the admin site
1. Create a few test products to see the site in action.
1. Open tab to `http://127.0.0.1:8000` to see the main site, with your new books.
