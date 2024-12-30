Social Media API
A Django-based API for a social media platform that allows users to create posts, follow other users, and view a personalized feed.

Features
User Registration and Profile Management
Post Creation, Update, and Deletion
Follow/Unfollow Users
User Feed Showing Posts from Followed Users
Installation
Prerequisites
Python 3.8+
pip
Setup Instructions
Clone the repository:

git clone https://github.com/yourusername/social-media-api.git
cd social-media-api
Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Set up the database:

python manage.py migrate
Create a superuser to access the Django admin:

python manage.py createsuperuser
Run the development server:

python manage.py runserver
Access the API at http://127.0.0.1:8000/

Usage
To register a new user, send a POST request to /api/users/.
To create a post, send a POST request to /api/posts/.
To follow a user, send a POST request to /api/follow/.
API Authentication Setup
Overview
This document outlines how to set up token-based authentication for your Django API using Django REST Framework (DRF) and SimpleJWT.

Installation
Make sure to install the required packages:

pip install djangorestframework djangorestframework-simplejwt



### Step 6: Push Changes to GitHub

Once you have implemented this setup, commit your changes and push them to your GitHub repository.

### Conclusion

By following these steps, you should have successfully added basic authentication to your Django API using token-based authentication with Django REST Framework and SimpleJWT. If you have any further questions or run into issues, feel free to ask!
