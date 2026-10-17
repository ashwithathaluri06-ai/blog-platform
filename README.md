# 📝 Blog Platform

A simple and user-friendly blogging web application built using **Python, Flask, and SQLite**. Users can create accounts, log in securely, publish blog posts, edit or delete their own posts, and interact through comments.

## 🚀 Features

- **User Authentication** — User registration and login.
- **Create Blog Posts** — Write and publish blog articles.
- **Edit Posts** — Update previously published content.
- **Delete Posts** — Remove your own blog posts.
- **Comments** — Interact with blog posts through comments.
- **Database Integration** — Store users, posts, and comments using SQLite.
- **Session Management** — Manage authenticated users using Flask-Login.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Backend Framework:** Flask
- **Database:** SQLite
- **ORM:** Flask-SQLAlchemy
- **Authentication:** Flask-Login
- **Frontend:** HTML, CSS, Bootstrap (if implemented)

## 📂 Project Structure

```text
blog-platform/
├── app.py
├── templates/
├── static/
├── instance/
├── requirements.txt
└── README.md
```

*Note: The structure above is illustrative. Adjust it to match your actual project files.*

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/ashwithathaluri06-ai/blog-platform.git
```

### 2. Navigate to the project folder

```bash
cd blog-platform
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
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

*Make sure your Flask application initializes the database and uses port 5000 before running these commands.*

## 🔐 Security Notes

- Do not upload passwords, secret keys, or other sensitive information.
- Use secure password hashing for user authentication.
- Configure a strong secret key through environment variables before deployment.

## 🎯 Learning Outcomes

This project demonstrates practical experience with:

- Python web development using Flask.
- CRUD operations (Create, Read, Update, Delete).
- Relational database integration.
- User authentication and session management.
- Building and organizing a full-stack web application.

## 👩‍💻 Author

**Ashwitha Thaluri**

- GitHub: [@ashwithathaluri06-ai](https://github.com/ashwithathaluri06-ai)
- LinkedIn: [Ashwitha Thaluri](https://www.linkedin.com/in/ashwitha-thaluri-55b33039a/)

---

⭐ If you find this project useful, consider giving the repository a star!

*Built with Python and Flask as a web development learning project.*
