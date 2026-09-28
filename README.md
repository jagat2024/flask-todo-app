# 📝 Flask Todo App

A simple and modern **Todo Management Web Application** built using **Python Flask, SQLite, SQLAlchemy, HTML, CSS, and JavaScript**.

This project helped me understand how a frontend form communicates with a Flask backend and how data is stored, updated, retrieved, and deleted from a database.

## 🚀 Features

* ➕ Create new Todos
* 📋 View all Todos
* ✏️ Update existing Todos
* 🗑️ Delete Todos
* 💾 SQLite database integration
* 🧩 SQLAlchemy ORM
* 🎨 Responsive modern UI
* 🌙 Dark / Light theme
* 📱 Mobile-friendly design

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript, Bootstrap
* **Backend:** Python, Flask
* **Database:** SQLite
* **ORM:** Flask-SQLAlchemy
* **Template Engine:** Jinja2

## 📂 Project Structure

```text
Flask/
│
├── app.py
├── requirements.txt
├── Procfile
├── .gitignore
│
├── templates/
│   ├── index.html
│   └── Update.html
│
├── static/
│   └── style.css
│
└── instance/
    └── todo.db
```

## ⚙️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/jagat2024/flask-todo-app.git
```

### 2. Move into the project directory

```bash
cd flask-todo-app
```

### 3. Create a virtual environment

```bash
python -m venv env
```

### 4. Activate the virtual environment

**Windows:**

```bash
env\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirement.txt
```

### 6. Run the application

```bash
python app.py
```

The application will be available at:

```text
http://127.0.0.1:5000
```

## 🔄 CRUD Operations

| Operation | Description           |
| --------- | --------------------- |
| Create    | Add a new Todo        |
| Read      | Display saved Todos   |
| Update    | Edit an existing Todo |
| Delete    | Remove a Todo         |

## 📚 What I Learned

Through this project, I learned:

* Flask routing
* GET and POST requests
* HTML forms and backend integration
* `request.form`
* Jinja2 templates
* Dynamic routes
* Flask-SQLAlchemy
* Database CRUD operations
* SQLite integration
* Template rendering
* Git and GitHub
* Basic deployment preparation

## 🔮 Future Improvements

* User authentication and registration
* Todo completion status
* Search and filtering
* PostgreSQL database
* REST API
* Production deployment
* Better validation and error handling

## 👨‍💻 Author

**Jagat Prasanna Shaw**

GitHub:
https://github.com/jagat2024

---

⭐ If you find this project useful, feel free to explore the repository.
