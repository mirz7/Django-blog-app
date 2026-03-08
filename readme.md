<div align="center">

# ✍️ Django Blogging System

*A clean, fully-featured blogging platform built with Python & Django.*

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-4.x-092E20?style=flat-square&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/Database-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

</div>

---

https://github.com/user-attachments/assets/d520489d-45e8-4ece-b74d-0221c861373f

---

## 📖 Overview

A robust blogging platform with an engaging reader-facing frontend and a comprehensive author dashboard. Whether you're sharing ideas, building a categorized knowledge base, or fostering community discussions — this system has you covered.

---

## ✨ Features

### 🌐 Frontend Experience
| Feature | Description |
|---|---|
| 🏠 Dynamic Homepage | Featured posts, latest articles & About Us section |
| 🗂️ Category Browsing | Filter and explore posts by category |
| 🔍 Rich Search | Search across titles, descriptions, and content |
| 💬 Comments | Authenticated users can comment on any post |

### 🛡️ Dashboard & Admin Panel
| Feature | Description |
|---|---|
| 🔐 Authentication | Secure register, login & logout via Django |
| 📁 Categories | Add, edit and delete blog categories |
| 📝 Post Management | Rich post editor with image uploads, slugs, draft/publish & featured flags |
| 👥 User Management | View, add, edit and remove platform users |

---

## 🛠️ Tech Stack

```
Backend    →  Python · Django 4.x
Database   →  SQLite (development default)
Frontend   →  HTML · CSS · Django Templates
Media      →  Django native file/image handling
```

---

## ⚙️ Getting Started

```bash
# 1. Clone the repository
git clone <your-repo-url>
cd blogging-system-yt

# 2. Create & activate a virtual environment
python -m venv venv
source venv/bin/activate      # macOS/Linux
# venv\Scripts\activate       # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Apply migrations
python manage.py makemigrations
python manage.py migrate

# 5. Start the development server
python manage.py runserver
```

> 🌍 Open your browser at **`http://127.0.0.1:8000/`**

---

## 🗂️ Project Structure

```
Django-blog-app/
│
├── blog_main/        # Core config, base URLs & auth views
├── blogs/            # Models (Category, Blog, Comment), views & search
├── dashboards/       # Author panel — full CRUD for content management
├── assignments/      # Static-like data (e.g. About Us)
├── templates/        # Centralised HTML templates
├── media/            # Uploaded images & files
├── manage.py
└── requirements.txt
```

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!
Feel free to open a [pull request](../../pulls) or file an [issue](../../issues).

---

<div align="center">
  <sub>Built with ❤️ using Django</sub>
</div>
