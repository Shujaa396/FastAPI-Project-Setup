# 🚀 FastAPI Backend Setup – Nexus POS (Week 1)

A production-ready backend foundation built with **FastAPI**, **PostgreSQL**, and a modular architecture. Includes database models, API setup, and system health routes.

---

## 🛠️ Tech Stack  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-000000?style=for-the-badge&logo=python&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)

---

## 📖 Overview  
This backend project initializes the **Week 1 Task** of the Nexus POS Internship. It provides a fully-structured FastAPI backend with PostgreSQL integration, modular folder setup, database tables, and health testing routes.

### Features:
- ⚙️ Modular folder architecture  
- 🗄️ PostgreSQL integration using SQLAlchemy/SQLModel  
- 🔗 `/ping` API for health check  
- 🧱 Tables for Users, Profiles, Subscriptions & POS Modules  
- 🧪 Tested through Postman & PgAdmin  
- 📦 Seed data included  

---

## 📁 Folder Structure  
```
project/
├── routes/
├── models/
├── schemas/
├── database/
├── main.py
└── README.md
```

---

## 📦 Setup Instructions  

1. Clone the repository:
```bash
git clone https://github.com/YourUsername/NexusPOS-Backend-Setup.git
```

2. Create a virtual environment:
```bash
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the FastAPI server:
```bash
uvicorn main:app --reload
```

5. Check the API:
```
http://127.0.0.1:8000/ping
```

---

## 🧩 Project Milestones  

| Milestone | Status |
|-----------|--------|
| FastAPI server running | ✅ |
| PostgreSQL connected | ✅ |
| Database tables created | ✅ |
| `/ping` route tested | ✅ |
| Seed data inserted | ✅ |
| `.env.example` added | ✅ |
| Code pushed to GitHub | ✅ |

---

## 🧪 Verification  
- Postman screenshots  
- PgAdmin database schema screenshots  
- GitHub commit logs  

---

## 🧠 Reflective Summary  
- FastAPI project structured cleanly for scalability.  
- PostgreSQL connected and tested with real queries.  
- JSON responses optimized for frontend integration.  
- Tools like VS Code & debugging assistants helped streamline the process.  

---

## 👤 Author  

**Syed Shujaa Hussain**  
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:web.shujaa10@gmail.com)  
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shujaa396)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syed-shujaa-hussain-69113b289)
