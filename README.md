# FastAPI User API

## 📌 Description
This project is a simple **REST API built with FastAPI** that provides basic user management features.
It is designed as a **clean, scalable backend foundation** that can be extended with authentication,
databases, CI/CD pipelines, and cloud deployment.

The application is **containerized using Docker**, ensuring consistency across development and production environments.

---

## 🚀 Features
- RESTful API built with FastAPI
- Clean and modular project structure
- Automatic API documentation with Swagger (OpenAPI)
- Dockerized application for easy deployment
- Ready to be extended with authentication, database, and CI/CD

---

## 🛠️ Tech Stack
- **Python 3.10**
- **FastAPI**
- **Uvicorn**
- **Docker**

---

## 📂 Project Structure
fastapi-user-api/
├── app/
│ └── main.py
├── Dockerfile
├── requirements.txt
└── README.md

## ▶️ Run the project locally (without Docker)

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload


http://127.0.0.1:8000/docs
🐳 Run the project with Docker
bash
Copier le code
docker build -t fastapi-user-api .
docker run -p 8000:8000 fastapi-user-api
Open:

bash
Copier le code
http://localhost:8000/docs
🔮 Future Improvements
User CRUD operations

Authentication with JWT

Database integration (PostgreSQL)

CI/CD with GitHub Actions

Cloud deployment (AWS / Azure / GCP)
