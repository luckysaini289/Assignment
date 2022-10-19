# django-login-logout
In this project, we implement a simple user authentication system by using the Django auth module. This system can handle the below mentioned functionalities.

New user registration
User login
Logout
Dynamic home page
Change password for existing user
Recommend secure password to user while signing up
Dynamic profile page for each user - profile includes username, details, display picture and bio
Edit/Update profile (display picture, bio) for logged-in user



Create a virtual environment and activate it. Not required but highly recommended.
python -m venv env
.\env\Scripts\activate
The above command is for Windows only. For Linux based operating systems, use the below mentioned command.

python3 -m venv env
source env/bin/activate
Now, install the requirements.
pip install -r requirements.txt
Now, migrate changes to the database and start the server.
python manage.py migrate
python manage.py runserver
