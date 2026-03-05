\# FlaskAuthApp



FlaskAuthApp is a simple authentication web application built using Flask and SQLAlchemy.  

This project implements secure user registration, login, session handling, and protected dashboard access.



------------------------------------------------------------



FEATURES



\- User Registration

\- User Login

\- Secure Password Hashing using bcrypt

\- Session Management

\- Protected Dashboard Route

\- Logout Functionality



------------------------------------------------------------



BUG FIX IMPLEMENTED (Assignment Requirement)



The registration validation bug has been fixed using proper server-side validation in Flask.



Backend Validation Added:



1\. Name cannot be empty

2\. Email cannot be empty

3\. Password cannot be empty

4\. Password must be at least 6 characters

5\. Email must be unique (duplicate email registration prevented)



Validation is implemented in the Flask backend (not just using HTML required attribute).



------------------------------------------------------------



DATABASE-LEVEL PROTECTION



The User model includes:



\- nullable=False for name, email, and password

\- unique=True for email

\- Secure password hashing using bcrypt



This ensures validation at both application level and database level.



------------------------------------------------------------



TECHNOLOGIES USED



\- Python

\- Flask

\- Flask-SQLAlchemy

\- SQLite

\- bcrypt

\- Bootstrap (Frontend)



------------------------------------------------------------



PROJECT STRUCTURE



FlaskAuthApp/

│

├── app.py

├── requirements.txt

├── README.md

│

├── templates/

│   ├── base.html

│   ├── index.html

│   ├── register.html

│   ├── login.html

│   └── dashboard.html

│

└── instance/



------------------------------------------------------------



HOW TO RUN LOCALLY



1\. Clone the repository:

&nbsp;  git clone https://github.com/dushyant2006/Flask_Auth_app.git



2\. Navigate into the project:

&nbsp;  cd Flask\_Auth\_app



3\. Create virtual environment:

&nbsp;  python -m venv venv

&nbsp;  venv\\Scripts\\activate



4\. Install dependencies:

&nbsp;  pip install -r requirements.txt



5\. Run the application:

&nbsp;  python app.py



Open browser and visit:

http://127.0.0.1:5000/



------------------------------------------------------------



DEPLOYMENT



This project is deployed on Render.



Live URL: https://flask-auth-app-msnr.onrender.com



------------------------------------------------------------



ASSIGNMENT COMPLETION



\- Registration validation bug fixed

\- Proper backend validation implemented

\- Repository is public on GitHub

\- Application deployed successfully on Render



------------------------------------------------------------





