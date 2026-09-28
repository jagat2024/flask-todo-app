# 📝 Flask Todo App

A simple and beginner-friendly **Todo Web Application** built using **Python Flask**, **Flask-SQLAlchemy**, and **SQLite**.

The application allows users to create, view, update, and delete their todo tasks.

## 🚀 Live Demo

👉 **[Flask Todo App](https://flask-todo-app-you0.onrender.com/)**

## 🛠️ Tech Stack

* **Python**
* **Flask**
* **Flask-SQLAlchemy**
* **SQLite**
* **HTML**
* **CSS**
* **Jinja2**
* **Gunicorn**
* **Render** – Deployment

## ✨ Features

* ➕ Add new todo
* 📋 View all todos
* ✏️ Update existing todos
* 🗑️ Delete todos
* 💾 SQLite database integration
* 🔗 Flask routing
* 🎨 HTML/CSS frontend
* ☁️ Deployed on Render

## 📂 Project Structure

```text
flask-todo-app/
│
├── static/
│   └── style.css
│
├── templates/
│   ├── index.html
│   └── update.html
│
├── app.py
├── todo.db
├── requirement.txt
├── Procfile
├── README.md
└── .gitignore
```

## ⚙️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/jagat2024/flask-todo-app.git
```

### 2. Navigate into the project

```bash
cd flask-todo-app
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirement.txt
```

### 6. Run the application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

## 🌐 Deployment

This project is deployed using **Render** with Gunicorn.

### Build Command

```bash
pip install -r requirement.txt
```

### Start Command

```bash
gunicorn app:app
```

## 📌 Future Improvements

* User authentication and registration
* Todo categories
* Task deadlines
* Task completion status
* Search and filtering
* PostgreSQL database
* Better responsive UI

## 👨‍💻 Author

**Jagat Prasanna Shaw**

GitHub: [jagat2024](https://github.com/jagat2024)

---

⭐ If you found this project useful, consider giving it a star!
