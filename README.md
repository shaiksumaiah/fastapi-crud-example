# 🚀 FastAPI CRUD App

[![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100.0-green?logo=fastapi)](https://fastapi.tiangolo.com/)
[![SQLite](https://img.shields.io/badge/SQLite-3.40-lightgrey?logo=sqlite)](https://www.sqlite.org/)

A beginner-friendly **FastAPI CRUD application** with **SQLite** database and **Pydantic validation**.

---

## 🧩 Features
- ✅ Create, Read, Update, and Delete users (CRUD)
- ✅ Data validation with **Pydantic**
- ✅ SQLite database using **SQLAlchemy**
- ✅ Interactive API docs at `/docs` (Swagger UI)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/shaiksumaiah/fastapi-crud-example.git
cd fastapi-crud-app
2️⃣ Install dependencies
bash
Copy code
pip install fastapi uvicorn sqlalchemy pydantic
▶️ Run the Application
bash
Copy code
uvicorn main:app --reload
Open your browser and go to:
👉 http://127.0.0.1:8000/docs

You’ll see Swagger UI where you can test all endpoints interactively.

📂 Project Structure
graphql
Copy code
fastapi-crud-app/
│
├── main.py              # Main FastAPI app with endpoints
├── models.py            # Database tables (SQLAlchemy models)
├── schemas.py           # Pydantic models for request & response validation
├── database.py          # Database connection setup
├── crud.py              # CRUD functions for database operations
├── .gitignore           # Files/folders Git should ignore
└── README.md            # This file - project description & instructions
🛠 Usage Examples
Create a user (POST)
URL: /users/

Body:

json
Copy code
{
  "name": "Aahil",
  "email": "aahil@example.com",
  "age": 22
}
Get all users (GET)
URL: /users/

Update a user (PUT)
URL: /users/{id}

Body:

json
Copy code
{
  "name": "Aahil Updated",
  "age": 23
}
Delete a user (DELETE)
URL: /users/{id}

🧠 Author
Shaik Sumaiah
Learning FastAPI, CRUD, and REST APIs with Python.

🛡 License
MIT License

✨ Made with ❤️ using FastAPI, SQLAlchemy, and Pydantic

yaml
Copy code

---

You just need to:

1. Open Notepad in your project folder:  
```bash
notepad README.md
Paste the above content

Save (Ctrl + S) and close Notepad

After that, you can do:

bash
Copy code
git add README.md
git commit -m "Resolved merge conflict and added professional README"
git push -u origin main
Your GitHub repo will now have the clean, professional README with badges.


