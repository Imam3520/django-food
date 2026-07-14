🍴 Django Food App

A simple web application built with Django that allows users to browse food items, place orders, and manage restaurant menus.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Features

User authentication (Sign up / Login / Logout)

Browse available food items

place orders

Restaurant/Admin dashboard to manage food items

Order history for customers

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Tech Stack

Backend: Django

Frontend: HTML, CSS, Bootstrap

Database: SQLite

Other Tools: Git, GitHub, VS Code

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

📂 Project Structure

mysite/
│── food/              # Main app
│── users/             # Authentication & profiles
│── templates/         # HTML templates
│── static/            # CSS, JS, images
│── db.sqlite3         # Database (local)
│── manage.py          # Django management script

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

⚙️ Installation

Clone the repository
  git clone https://github.com/Imam3000/django-food.git
  cd django-food

Create a virtual environment
  python -m venv env
  source env/bin/activate   # On Linux/Mac
  env\Scripts\activate      # On Windows

Install dependencies
  pip install -r requirements.txt

Run migrations
  python manage.py migrate

Create a superuser
  python manage.py createsuperuser

Start the server
  python manage.py runserver

Open in browser → http://127.0.0.1:8000

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

🧑‍💻 Usage

Register/Login as a customer

Browse menu & place orders

Login as admin to manage food items
