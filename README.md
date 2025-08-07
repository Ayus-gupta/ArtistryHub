# 🎭 Artist-Audience Show Platform

This is a Flask-based web application where:
- **Artists** can register, log in, create shows, view audience interest and likes.
- **Audience** members can register, log in, like performances, request specific art forms, and share artist shows on various platforms.

---

## 🚀 Features

### 👩‍🎤 For Artists:
- Register/Login as artist
- Create and manage shows
- View how many people liked their shows
- See performance requests from audience

### 👨‍👩‍👧‍👦 For Audience:
- Register/Login as audience
- Like artist shows
- Request performances (e.g., dance, storytelling)
- Share artist shows on social media platforms

---

## 🧱 Tech Stack

- **Backend**: Flask (Python)
- **Database**: SQLite (via SQLAlchemy ORM)
- **Frontend**: HTML, Bootstrap (Jinja2 templating)

---

## 📁 Project Structure

```bash
├── app/
│   ├── __init__.py
│   ├── models.py
│   ├── routes.py
│   ├── forms.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── dashboard.html
│   │   └── ...
├── static/
│   └── style.css
├── config.py
├── run.py
├── requirements.txt
└── README.md
