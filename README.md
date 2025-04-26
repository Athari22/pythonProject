# 📝 Flask Blog with User Authentication, Comments, and Deployment

A full-featured blog web application built with Flask. It supports user registration and login, admin-only post creation/edit/delete, commenting, CKEditor integration, Gravatar avatars, PostgreSQL deployment, and Git version control.

## 🚀 Features

- 🧾 Create, read, update, and delete blog posts (CRUD)
- 👤 User authentication and registration using Flask-Login
- 🔐 Password hashing with Werkzeug
- 🛡 Admin-only access for editing/deleting posts
- 💬 Comment system for authenticated users
- 🌐 Rich-text editing with Flask-CKEditor
- 🖼 Gravatar support for user profile images
- 📦 PostgreSQL integration via SQLAlchemy ORM
- 🌍 Deployment-ready with Gunicorn and Render
- 🔐 Secrets and configs handled with environment variables

## 📸 Screenshots

- Blog homepage with posts
- Register/Login forms
- Admin post editor
- Comment section per post

## 🛠 Tech Stack

- **Backend**: Python, Flask, SQLAlchemy, Flask-Login, Flask-WTF
- **Frontend**: HTML, Bootstrap, Jinja2, CKEditor
- **Database**: SQLite (dev), PostgreSQL (production)
- **Deployment**: Gunicorn, Render
- **Version Control**: Git + GitHub

## 🗃 Project Structure

day-71-starting-files-blog-for-deployment/
│
├── main.py                  # Main application file with routes, models, and logic
├── forms.py                 # Flask-WTF forms for registration, login, and post creation
├── requirements.txt         # List of Python dependencies
├── Procfile                 # Configuration file for deployment with gunicorn
├── .gitignore               # Git ignore rules for unnecessary files
├── .env                     # (Optional) Environment variables for local development
│
├── templates/               # Jinja2 HTML templates
│   ├── base.html            # Base layout template
│   ├── index.html           # Homepage displaying all blog posts
│   ├── register.html        # User registration page
│   ├── login.html           # User login page
│   ├── make-post.html       # Page to create/edit blog posts
│   ├── post.html            # Individual post page with comment form
│   ├── about.html           # About page
│   └── contact.html         # Contact page
│
├── static/                  # Static files like CSS and images
│   ├── css/
│   │   └── styles.css       # Custom stylesheet
│   └── assets/
│       └── img/             # Images used in the blog (headers, avatars, etc.)


## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/flask-blog.git
cd flask-blog
....
Create a Virtual Environment
python -m venv venv
source venv/bin/activate  #On macOS/Linux
venv\Scripts\activate # On Windows

Install the dependencies
pip install -r requirements.txt

Run the application
python main.py

```



