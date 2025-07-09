# 🤝 Charity Project – Quera College

Welcome to the **Charity Project**, a Django-based application developed as part of the Quera Back-End College.  
This project simulates a real-world charity management system, where users can donate to various projects, track contributions, and manage project funding.

🎓 _This project was developed during the Quera educational program and received official certification upon completion._  

---

## 🧩 Overview

This training project includes core backend functionalities such as:

- 💰 **Charity Projects & Donations**  
  Users can donate to active projects and track how much each project has received.

- 👥 **User Management**  
  Basic authentication and permission system using JWT.

- 📊 **Funding Calculation**  
  Projects are automatically marked as completed when fully funded.

- 🔒 **Secure API**  
  Endpoints are protected based on user permissions (superuser vs. normal user).

---

## 🔧 Features

- JWT-based Authentication (Login/Register)
- User roles and permission control
- CRUD operations for charity projects
- Donation system with funding updates
- Auto-close project on full funding
- Admin-only access to edit/delete projects
- Custom validators to ensure clean data
- Pagination & filtering for large datasets
- Clean and RESTful API design

---

## 📦 Technologies Used

- 🐍 Python 3.x  
- 🕸️ Django 4.x  
- ⚙️ Django REST Framework  
- 🔐 Simple JWT for authentication  
- 📚 DRF permissions & validators  
- 📦 SQLite for development  
- 🧪 Pytest (optional for testing)

---

## 🚀 Getting Started

### ✅ Backend Setup

```bash
git clone https://github.com/Behnoushin/Charity-Project
cd Charity-Project

# Create virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start development server
python manage.py runserver
```

---

### 🗂️ App Structure

charity_project – Main logic for managing projects and donations
users – Handles user authentication and permissions
core – Shared logic, settings, and configs

---

### 📜 License
This project was developed for educational purposes as part of the Quera bootcamp.
All rights belong to their respective authors and contributors.


Crafted with ❤️ by Behnoushin (Behnoush Shahraeini)
