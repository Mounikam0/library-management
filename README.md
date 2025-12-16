# Library Management System (Django)

A Django-based application to manage books with CRUD functionality.

## Features
- Add books
- View books
- Delete books
- Admin panel support

## Tech Stack
- Python 3.11
- Django 4.2
- SQLite

## Setup Instructions
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
