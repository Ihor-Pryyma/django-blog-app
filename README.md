# Blog Project with Django 4

![Django Version](https://img.shields.io/badge/Django-4.1-brightgreen)
![Python Version](https://img.shields.io/badge/Python-3.10%2B-brightgreen)

This project is a Django-based blog application.

## Features

- User-friendly blog interface.
- Blog post creation, editing, and deletion.
- Search system.
- Comment system.
- RSS feed for blog posts.
- Responsive design for various screen sizes.

## Getting Started

To run this project locally, make sure you have the following prerequisites installed:

- Python (3.10+)
- Django (4.0)
- Git

Follow these steps to set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/Ihor-Pryyma/django-blog-app
   ```
2. Navigate to the project directory:
   ```bash
   cd django-blog-app
   ``` 
3. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use "venv\Scripts\activate"
   ``` 
4. Install the project dependencies:
   ```bash
   pip install -r requirements.txt
   ``` 
5. Apply database migrations:
   ```bash
   python manage.py migrate
   ``` 
6. Create a superuser for the admin interface:
   ```bash
   python manage.py createsuperuser
   ```
7. Run the development server:
   ```bash
   python manage.py runserver
   ```
8. Access the blog application at http://localhost:8000/blog/ and the admin interface at http://localhost:8000/admin/.

## Usage
- Visit the blog application to view and interact with blog posts.
- Log in to the admin interface to manage blog posts, comments, and users.

## RSS Feed
This project includes an RSS feed for blog posts. You can access the RSS feed by visiting http://localhost:8000/blog/feed/.

## Acknowledgments
- [Antonio Mele](https://github.com/AMELANIE/): Author of "Django 4 by Example."
