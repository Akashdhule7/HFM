# HFM Task
# Registration Page Project by using Python, Django, HTML, CSS, Bootstrap5

This is a simple **Django-based registration page** with validation and responsive UI.


## Features
1. User registration with username, email, password, country, and phone number.
2. Validations using Django forms.
3. Frontend validation for phone number with country code auto-fill.
4. Success and error messages displayed on the page.
5. Responsive and modern design with custom CSS and Bootstrap5.
6. Simulated database storage using a Python dictionary (no database required).

## Project Structure

│
├── hfmsite/
│   ├── settings.py
│   ├── urls.py
│   └── asgi.py / wsgi.py etc.
│
├── login_app/
│   ├── templates/
│   │   ├── register.html
│   │   ├── index.html
│   │   └── nav.html
│   │
│   ├── static/
│   │   └── style.css
│   │
│   ├── admin.py
│   ├── urls.py
│   ├── forms.py
│	├── test.py
│	├── views.py
│   └── models.py
│
└── manage.py
└── README.md
└── requirement.txt

1) Create a project

2) Create and activate a virtual environment:
python -m venv venv
# Windows
venv\Scripts\activate
# Linux / Mac
source venv/bin/activate

3) Install dependencies
pip install -r requirements.txt

4) Run the Project/Django server
python manage.py runserver

    4.1) For testing I have created test case.
         
         # Run the below command to test with test cases
         python manage.py test login_app

5) Open brower/link
http://127.0.0.1:8000/




