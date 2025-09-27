# ALX Travel App

A Django-based web application for managing travel-related data and bookings. This project is part of the ALX Software Engineering curriculum.

## Features

- User authentication and management
- CRUD operations for travel destinations and bookings
- Admin dashboard for managing users and content
- Seed data for quick setup
- REST API endpoints for integration with frontend or mobile apps

## Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd alx_travel_app_0x00

python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
pip install -r requirements.txt
Run migrations:
```
python manage.py makemigrations
python manage.py migrate
Create a superuser (optional):


python manage.py createsuperuser
Seed the database:


python manage.py seed
Start the development server:


python manage.py runserver
Usage
Visit http://127.0.0.1:8000/ in your browser

Login as admin to manage travel destinations and users

API endpoints available under /api/ (if implemented)

Technologies Used
Python 3.12

Django

Django REST Framework (if APIs implemented)

SQLite (default, can be changed to PostgreSQL/MySQL)

django-environ for environment variable management

django-cors-headers for CORS support

Contributing
Fork the repository

Create a new branch: git checkout -b feature/your-feature

Commit your changes: git commit -m "Add your feature"

Push to the branch: git push origin feature/your-feature

Open a Pull Request

License
This project is licensed under the MIT License.