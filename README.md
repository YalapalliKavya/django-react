# 🚀 Django + React Full Stack Application

This project is a **Full Stack Web Application** built using **Django (Backend)** and **React (Frontend)**.
The backend provides REST APIs while the React frontend consumes these APIs to display dynamic data in the user interface.

---

# 🧑‍💻 Tech Stack

### Backend

* Python
* Django
* Django REST Framework

### Frontend

* React.js
* JavaScript
* HTML
* CSS

### Database

* SQLite (default Django database)

---

# 📂 Project Structure

```
django-react
│
├── backend
│   ├── manage.py
│   ├── db.sqlite3
│   └── django project files
│
├── frontend
│   ├── package.json
│   ├── src
│   └── public
│
└── README.md
```

---

# ✨ Features

* Full Stack Web Application
* REST API using Django
* React Frontend Interface
* API communication between React and Django
* Modular project structure

---

# ⚙️ Installation Guide

## 1️⃣ Clone the repository

```
git clone https://github.com/YalapalliKavya/django-react.git
```

```
cd django-react
```

---

# 🐍 Backend Setup (Django)

Create virtual environment:

```
python -m venv env
```

Activate environment:

Windows

```
env\Scripts\activate
```

Install dependencies:

```
pip install django djangorestframework
```

Run migrations:

```
python manage.py migrate
```

Start Django server:

```
python manage.py runserver
```

Backend will run on:

```
http://127.0.0.1:8000
```

---

# ⚛️ Frontend Setup (React)

Navigate to frontend folder:

```
cd frontend
```

Install dependencies:

```
npm install
```

Start React server:

```
npm start
```

React will run on:

```
http://localhost:3000
```

---

# 🔗 API Communication

React sends requests to the Django backend API to:

* Fetch data
* Create new records
* Update records
* Delete records

---

# 🚀 Future Improvements

* User authentication (Login / Register)
* JWT authentication
* Deployment (Render / Vercel / AWS)
* UI improvements
* Pagination and filtering

---

# 👩‍💻 Author

**Kavya Yalapalli**

GitHub:
https://github.com/YalapalliKavya

---

⭐ If you like this project, please give it a **star** on GitHub.
