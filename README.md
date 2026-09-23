# 💸 BillSmart – Smart Bill Management System

## 📌 Overview

BillSmart is a web-based application designed to help users manage their bills efficiently.
It allows users to track expenses, categorize bills, and receive reminders, all in a simple and user-friendly interface.

---
## 🌐 Live Demo
👉 https://billsmartapp.onrender.com
---
## 🚀 Features

* 🔐 Google OAuth Login Authentication
* 📊 Dashboard with Expense Overview
* 🧾 Add, View, and Manage Bills
* 📂 Category-wise Expense Tracking
* ⏰ Reminder System (Email / WhatsApp Ready)
* 📉 Data Visualization using Charts
* 💻 Responsive UI

---

## 🛠️ Tech Stack

### 🔹 Backend

* Python
* Flask
* Flask-SQLAlchemy

### 🔹 Frontend

* HTML
* CSS
* Jinja2 Templates

### 🔹 Database

* SQLite (Current)
* PostgreSQL (Initially used for cloud deployment)

### 🔹 Tools & Platforms

* VS Code
* Git & GitHub
* Render (Deployment)
* Chart.js

---

## 📂 Project Structure

```
BillSmartApp/
│── static/
│   ├── css/
│   ├── js/
│
│── templates/
│   ├── login.html
│   ├── dashboard.html
│   ├── add_bill.html
│
│── app.py
│── requirements.txt
│── billsmart.db
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Ala-Ganesh/BillSmartApp.git
cd BillSmartApp
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
flask run
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## 🗄️ Database Info

* SQLite is used for local development and demo.
* Database file: `billsmart.db`
* Tables are created using:

```python
from app import db
db.create_all()
```

---

## 🔐 Authentication

* Google OAuth is used for secure login.
* User session is maintained using Flask sessions.

---

## 🌐 Deployment

* Deployed on **Render**
* PostgreSQL was used initially for production
* Switched to SQLite for stability and demo purposes

---

## 🎯 Future Enhancements

* Mobile app integration
* Advanced analytics
* AI-based expense insights
* Real-time notifications

---

## 👨‍💻 Author

**Ala Ganesh**
B.Tech CSE (Data Science)

---

## 📜 License

This project is for educational purposes only.
