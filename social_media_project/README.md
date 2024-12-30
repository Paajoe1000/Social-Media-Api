SOCIAL-MEDIA API

Overview
This project is a Social Media API built using Django and Django REST Framework. It includes core functionalities for managing users, posts, comments, likes, follows, notifications, and user authentication. The goal of this project is to provide a backend for a social media platform where users can interact by creating posts, following other users, commenting on posts, liking content, and receiving notifications for various activities.

Features
User Management User registration, login, and profile management.
JWT-based authentication for securing endpoints.
Profile creation with bio and profile picture (stored in PostgreSQL).
Post Management Full CRUD operations (create, read, update, delete) for posts.
Follow System Follow and unfollow other users. Prevent users from following themselves.
Display a feed of posts from followed users.
Comment & Like System Comment on posts and view comments.
Like and unlike posts. Prevent users from liking the same post multiple times.
Notifications Users receive notifications for likes, comments, and new followers. Notifications system is implemented to ensure users stay informed.
Tech Stack
Backend Framework: Django, Django REST Framework
Database: PostgreSQL
Authentication: JWT (JSON Web Tokens) via djangorestframework-simplejwt
Installation
Prerequisites
Python 3.x
PostgreSQL
Virtual Environment (optional but recommended)