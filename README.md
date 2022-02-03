# User-authentication-API

Database used - postgresql


Steps( run this in the virtual environment):
1) Open the terminal and got to the project folder.
2) Run the command "python manage.py makemigrations" and "python manage.py migrate".
3) Run the command "python manage.py runserver"
4) Now in postman Use POST request to url - http://127.0.0.1:8000/api/Register/ to register user details.
5) Write the user details in this format in the body and send the request
    {
    "username": "abcd",
    "email":"abcd@gmail.com",
    "password": "1234"
    } 
6) URL - http://127.0.0.1:8000/api/Login/ to login .
7) Write the user details in this format in the body and send the request to login.
     {
    "username": "abcd",
    "password": "1234"
    } 
