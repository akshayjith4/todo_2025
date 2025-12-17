# 📝 To-Do Web App (Django)

A clean, minimal **To-Do List web application** built using **Django**. This project demonstrates core backend concepts like models, views, templates, URL routing, and database persistence — implemented with proper Git workflow.

---

## 🚀 Features

* Add new tasks
* Mark tasks as completed / incomplete
* Delete tasks
* Persistent storage using SQLite
* Django Admin panel for task management
* Clean and simple UI

---

## 🛠 Tech Stack

* **Backend:** Django 6.0
* **Frontend:** HTML, CSS (Django Templates)
* **Database:** SQLite3
* **Version Control:** Git & GitHub

---

## 📂 Project Structure

```
tech_cake/
│
├── todo_project/        # Django project settings
├── tasks/               # Main app (models, views, urls)
├── templates/           # HTML templates
├── venv/                # Virtual environment (ignored in Git)
├── manage.py
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/akshayjith4/todo_2025.git
cd todo_2025
```

### 2️⃣ Create & activate virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install django
```

### 4️⃣ Run migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Create superuser (optional)

```bash
python manage.py createsuperuser
```

### 6️⃣ Run the server

```bash
python manage.py runserver
```

Open in browser: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🔐 Admin Panel

Access admin dashboard:

```
http://127.0.0.1:8000/admin/
```

Use the superuser credentials to manage tasks.

---

## 📌 Learning Outcomes

* Django project & app structure
* MVC (Model-View-Template) pattern
* CRUD operations
* URL routing & template rendering
* Git & GitHub workflow

---

## 📈 Future Improvements

* User authentication
* Per-user task lists
* AJAX / REST API
* Better UI (Bootstrap / Tailwind)
* Deployment (Render / Railway / AWS)

---

## 👨‍💻 Author

**Akshayjith**
Computer Science & Engineering Student

---

⭐ If you found this project useful, give it a star!
