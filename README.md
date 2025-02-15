# Personal Website Django Project

This is a simple Django project that serves a "Hello, World!" message at the URL `http://127.0.0.1:8000/`. It is built using Python 3.13.3 and includes the specified packages.

## Requirements

- Python 3.13.3
- asgiref==3.8.1
- Django==5.2a1
- sqlparse==0.5.3
- tzdata==2025.1

## Installation

To set up this project, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mgrecuccio/personalwebsite.git/
   cd personal_website

2. **Create a virtual environment:**

   ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install the required packages:**

   ```bash
    pip install asgiref==3.8.1 Django==5.2a1 sqlparse==0.5.3 tzdata==2025.1

4. **Install the required packages:**

   ```bash
    pip install asgiref==3.8.1 Django==5.2a1 sqlparse==0.5.3 tzdata==2025.1

5. **Create a new Django project:**

   ```bash
    django-admin startproject django_project .

6. **Run the server:**

   ```bash
    python manage.py runserver

7. **Access the application::**

   Open your browser and go to http://127.0.0.1:8000/ to see the "Homepage" message or navigate to http://127.0.0.1:8000/about for the about page.
   
