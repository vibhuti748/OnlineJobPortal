# 💼 Django Online Job Portal

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Online-brightgreen)](https://vibhuti11.pythonanywhere.com)


A Django-based web application designed to manage job postings and applications, enabling interaction between administrators, recruiters, and job seekers through a role-based system.

The project focuses on backend development using Django, covering authentication, database modeling, and template-based rendering.

---

## 🚀 Features

- Role-based authentication (Admin, Recruiter, Job Seeker)
- User registration and login system
- Job posting and management by recruiters
- Job search and filtering for job seekers
- User and recruiter profile management
- Admin panel for overall system control

---

## 🛠 Tech Stack

- **Backend:** Python, Django  
- **Database:** SQLite (development)  
- **Frontend:** HTML, CSS, JavaScript  

---

## 🧩 Project Structure

 ```
 django-online-job-portal/
├── jobportal/ # Project configuration
│ ├── settings.py
│ ├── urls.py
│ ├── asgi.py
│ └── wsgi.py
├── job/ # Core job portal application
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ ├── templates/
│ └── static/
├── media/ # Uploaded media files
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```


---

## 📌 Purpose of the Project

This project was developed to understand Django fundamentals such as user authentication, role-based access control, ORM-based database interactions, and form handling in a multi-user web application.

It also helped in learning how to structure Django projects and manage different user workflows within a single application.

---

## ▶️ Running the Project Locally

```bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---
