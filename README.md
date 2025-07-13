# alx_backend_caching_property_listings

This is a Django-based property listing web application with caching and containerized infrastructure using PostgreSQL and Redis via Docker Compose.

## 📌 Project Objective

The goal is to demonstrate backend caching using Redis in a Django application while setting up a production-like environment with Docker.

---

## 📦 Features

- ✅ Django 4+ project
- ✅ PostgreSQL as the relational database
- ✅ Redis as the caching backend
- ✅ Docker Compose for service orchestration
- ✅ Django models, migrations, and ORM setup
- ✅ Environment isolated with `venv`

---

## 🏗️ Project Structure

```bash
alx_backend_caching_property_listings/
│
├── alx_backend_caching_property_listings/   # Django project settings
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── properties/                              # Django app with Property model
│   ├── models.py
│   ├── views.py
│   └── admin.py
│
├── manage.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
└── db.sqlite3 (only if using SQLite locally)
