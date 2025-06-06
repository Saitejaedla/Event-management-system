Event Management System
A web-based platform that simplifies event and ground bookings for students and administrators. Users can register, view events, and book grounds, while admins manage events and view bookings. This system reduces manual effort, saves time, and ensures organized scheduling within institutions.

Features
User registration and login

Event viewing and booking

Ground booking management

Admin panel for managing events and bookings

Responsive and user-friendly interface

Technologies Used
Backend: Django (Python)

Frontend: HTML, CSS, JavaScript

Database: SQLite

Installation and Setup
Clone the repository:


git clone https://github.com/Saitejaedla/Event-management-system.git
Navigate to the project directory:


cd Event-management-system
Create a virtual environment (optional but recommended):


python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Install required packages:


pip install -r requirements.txt
Run migrations:


python manage.py migrate
Create a superuser (admin):


python manage.py createsuperuser
Run the development server:

bash
Copy code
python manage.py runserver
Open your browser and go to:

User interface: http://127.0.0.1:8000/scm/

Admin login: http://127.0.0.1:8000/admin

Usage
Users can register, log in, view available events, and book grounds.

Admin can log in via the admin panel to add/edit events and view all bookings.
