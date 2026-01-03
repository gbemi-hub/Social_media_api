Social Media API

A RESTful API built with Django and Django REST Framework that provides the core functionalities of a social media platform. Users can register, follow others, create posts, comment, like posts, and receive notifications for interactions.

Features

User Authentication

Custom user model with bio, profile picture, and following relationships.

Registration and login with token-based authentication.

Posts & Comments

Users can create, read, update, and delete posts.

Comment on posts with full CRUD functionality.

Follow System

Users can follow and unfollow others.

Personalized feed displaying posts from followed users.

Likes

Like and unlike posts.

Users cannot like the same post more than once.

Notifications

Receive notifications for:

New followers

Likes on posts

Comments on posts

Fetch a list of notifications, with unread ones first.

API Usability

RESTful endpoints.

Supports pagination for posts and comments.

Token authentication for secure access.
