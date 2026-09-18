# 📚 Library Management System

A full-featured web application built with Django for managing books and authors, implementing complete CRUD (Create, Read, Update, Delete) functionality.

## Features

- View list of all books
- View detailed information about a single book
- Add a new book
- Edit an existing book
- Delete a book
- Manage data through Django admin panel

## Tech Stack

- Python 3.12
- Django 6.1
- SQLite (database)
- HTML (Django Templates)

## Installation & Setup

1. Clone the repository:

git clone https://github.com/alkssandi-code/library-management-system.git
cd library-management-system

2. Create and activate a virtual environment:

python3 -m venv venv
source venv/bin/activate

3. Install required packages:

pip install -r requirements.txt

4. Apply database migrations:

python manage.py migrate

5. Create an admin user:

python manage.py createsuperuser

6. Run the development server:

python manage.py runserver

7. Open in browser: http://127.0.0.1:8000/

## Author

Alkssandi