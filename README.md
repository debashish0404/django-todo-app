# 📝 Django To-Do List Web App

A fully functional To-Do List web application built using Django. This project allows users to manage their daily tasks efficiently with features like adding, updating, deleting, and marking tasks as completed.

---

---

## 📌 Features

* Add new tasks
* Edit/update tasks
* Delete tasks
* Mark tasks as completed
* Simple and clean UI
* Fast and lightweight

---

## 🛠️ Tech Stack

* Backend: Django (Python)
* Frontend: HTML, CSS
* Database: SQLite

---

## 📂 Project Structure


todo_project/
│
├── todo_app/
│   ├── migrations/
│   ├── templates/
│   │   └── todo_app/
│   │       ├── index.html
│   │       ├── update_task.html
│   │
│   ├── static/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│
├── todo_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   ├── wsgi.py
│
├── db.sqlite3
├── manage.py
└── requirements.txt

---

## ⚙️ Installation & Setup Guide

### Step 1: Clone the Repository

bash
git clone https://github.com/your-username/django-todo-app.git
cd django-todo-app

### Step 2: Create Virtual Environment

bash
python -m venv venv

### Step 3: Activate Virtual Environment

Windows:

bash
venv\Scripts\activate

Mac/Linux:
bash
source venv/bin/activate


### Step 4: Install Dependencies

bash
pip install django


or

bash
pip install -r requirements.txt


### Step 5: Run Migrations

bash
python manage.py makemigrations
python manage.py migrate


### Step 6: Run Development Server

bash
python manage.py runserver


### Step 7: Open in Browser

http://127.0.0.1:8000/

---

## 📌 How It Works

1. User opens the homepage
2. Adds a new task
3. Tasks are displayed in a list
4. User can update, delete, or mark tasks as completed

---

## 📦 requirements.txt

Django>=4.0

---
 Future Enhancements

* User authentication (Login/Register)
* Due dates & reminders
* Task priority levels
* REST API using Django REST Framework
* Deployment on cloud platforms

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Debashish Mishra
CSE (2nd Year), Rungta College
Kalam Batch
Interested in AI, Machine Learning, and IoT

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
