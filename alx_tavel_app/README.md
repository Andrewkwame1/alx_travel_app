# ALX Travel App

A Django-based travel listing platform with REST API and Swagger documentation.

## Features

- Django REST Framework API
- MySQL database configuration
- Swagger API documentation at `/swagger/`
- CORS headers for cross-origin requests
- Environment variable management
- Celery for background tasks
- Listings app for travel listings management

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirement.txt
   ```

2. Configure environment variables in `.env` file

3. Run migrations:
   ```bash
   python manage.py migrate
   ```

4. Start the development server:
   ```bash
   python manage.py runserver
   ```

## API Documentation

Visit `/swagger/` for interactive API documentation.

## Project Structure

- `alx_travel_app/` - Main Django project
- `listings/` - Travel listings app
- `requirement.txt` - Project dependencies