# 📝 Task Master

A simple and efficient Task Management Web Application built using Flask and SQLite. Task Master helps users create, update, track, and delete daily tasks through a clean and responsive interface.

## 🚀 Live Demo

🌐 Website: 

---

## 📌 Features

- ✅ Create new tasks
- ✏️ Update existing tasks
- 🗑️ Delete tasks
- 📅 Automatic task creation timestamp
- 📋 View all tasks in chronological order
- 💾 Persistent storage using SQLite database
- 🌐 Web-based user interface
- 🚀 Ready for cloud deployment with Gunicorn

---

## 🛠️ Tech Stack

### Backend
- Python
- Flask
- Flask-SQLAlchemy
- Gunicorn

### Database
- SQLite

### Frontend
- HTML5
- CSS3
- Jinja2 Templates

---

## 📂 Project Structure

```text
Task Master/
│
├── app.py                  # Main Flask Application
├── requirements.txt        # Project Dependencies
├── Procfile                # Deployment Configuration
├── .gitignore              # Ignored Files
│
├── instance/
│   └── test.db             # SQLite Database
│
├── templates/
│   ├── base.html           # Base Template
│   ├── index.html          # Home Page
│   └── update.html         # Update Task Page
│
└── README.md
