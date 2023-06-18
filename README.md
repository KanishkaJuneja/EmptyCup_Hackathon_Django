# EmptyCup_Hackathon_Django
A Django Project for Register and Login.

Django Dashboard Project

This project is a Django-based web application that includes a login page, registration functionality, and a dashboard with multiple tabs. It utilizes Django's authentication system and custom user model for user management.

Features:
- User registration with email and password
- User login and authentication
- Dashboard with multiple tabs
- Logout functionality

Prerequisites:
- Python (3.6 or higher)
- Django (3.0 or higher)

Installation:
1. Clone the repository: git clone (https://github.com/KanishkaJuneja/EmptyCup_Hackathon_Django.git)
2. Navigate to the project directory: cd django-dashboard
3. Create a virtual environment: python -m venv env
4. Activate the virtual environment:
   - For Windows: env\Scripts\activate
   - For macOS/Linux: source env/bin/activate
5. Install the project dependencies: pip install -r requirements.txt
6. Run database migrations: python manage.py migrate

Usage:
1. Start the development server: python manage.py runserver
2. Open your web browser and access the following URL: http://localhost:8000/login
3. Use the provided registration form to create a new user account.
4. Login with your credentials on the login page.
5. You will be redirected to the dashboard with multiple tabs.

Important Note:
Please note that due to security barriers in the Chrome browser, certain features such as sending OTP emails may not work as expected. It is recommended to test the project in browsers other than Chrome (e.g., Firefox, Safari) for the best experience.

For more information and detailed code implementation, please refer to the project's source code.

