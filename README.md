# Ecommerce-Bookselling-Website
This is a Django-based web application for an online Book store. The project includes features for managing products, user authentication, and an e-commerce store.

Ecommerce-Bookselling-Website
Overview
This is a Django-based web application for an online book store named Novellanest. The project includes features for managing products, user authentication, and an e-commerce store.
Project Structure

inspectionProfiles/: Configuration files for code inspection.
django-novellanest/: Main Django project directory.
manage.py: Django management script.
media/: Directory for uploaded media files (e.g., book images).
templates/: HTML templates for the application.
venv/: Virtual environment for Python dependencies.
shop/: Main application directory containing models, views, and more.

Installation

Clone the repository:git clone <repository-url>
cd django-novellanest

Set up the virtual environment:python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install dependencies:pip install -r requirements.txt

Apply migrations:python manage.py migrate

Run the development server:python manage.py runserver

Usage

Access the application at http://127.0.0.1:8000/.
Use the admin panel at http://127.0.0.1:8000/admin/ after creating a superuser with python manage.py createsuperuser.

Contributing
Feel free to fork the repository and submit pull requests. Please ensure your code follows the project's coding standards.

