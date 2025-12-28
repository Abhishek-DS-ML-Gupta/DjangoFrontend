# 🚀 Django UI/UX Focused Web Application

A **production-ready Django web application** with a strong focus on **clean UI, smooth UX, and scalability**.  
Built using **Django best practices**, modular folder structure, and modern frontend techniques.

---

## ✨ Features

- 🔐 Secure Django backend
- 🎨 User-friendly UI/UX
- ⚡ Fast page interactions (HTMX ready)
- 🌙 Modern responsive design (Tailwind CSS)
- 🧩 Component-based templates
- 📦 Scalable app architecture
- 🔒 Environment-based configuration
- 🧠 Clean separation of backend & frontend logic

---

## 🏗️ Tech Stack

### Backend
- Python 3.x
- Django
- Django REST Framework (optional)

### Frontend
- Django Templates
- Tailwind CSS
- HTMX
- Alpine.js (optional)

### Tools
- Virtual Environment (`venv`)
- dotenv for secrets
- Git

---

## 📂 Project Structure
```bash
project-root/
│
├── manage.py
├── requirements.txt
├── .env
│
├── config/
│ ├── settings/
│ │ ├── base.py
│ │ ├── dev.py
│ │ └── prod.py
│ ├── urls.py
│ └── wsgi.py
│
├── apps/
│ ├── accounts/
│ ├── dashboard/
│
├── templates/
│ ├── base/
│ ├── components/
│ └── pages/
│
├── static/
│ ├── css/
│ ├── js/
│ └── images/
│
├── media/
└── venv/

```
---

## ⚙️ Setup Instructions (Windows / Linux / macOS)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Abhishek-DS-ML-Gupta/DjangoFrontend.git
cd your-repo-name
```
### 2️⃣ Create Virtual Environment
```bash
python -m venv venv
```
## Activate it

### Windows (PowerShell):
```bash
venv\Scripts\activate
```

## Linux / macOS:
```bash
source venv/bin/activate
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Environment Variables

#### Create a .env file:
```bash
SECRET_KEY=your-secret-key
DEBUG=True
```
5️⃣ Run Migrations
```bash
python manage.py migrate
```
### 6️⃣ Create Superuser
```bash
python manage.py createsuperuser
```
### 7️⃣ Run Development Server
```bash
python manage.py runserver
```

## Open browser:
```bash
http://127.0.0.1:8000/
```
