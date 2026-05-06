# 📧 DheeMail

DheeMail is a Django-based web application that simulates a simple email system.
Built using the **MVT (Model-View-Template)** architecture, this project focuses on user authentication, messaging, and clean backend design.


## 🚀 Features

* 🔐 Custom User Authentication
* 📬 Send & Receive Messages
* 📨 Inbox & Sent Mail System
* 🧑‍💼 Custom User Model
* 🛠 Admin Panel Access
* 💾 SQLite Database
* 🎯 Clean and modular Django structure



## 🏗 Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS
* **Database:** SQLite
* **Architecture:** MVT (Model-View-Template)

---

## 📁 Project Structure

```
dheemail/
│
├── dheemail/          # Project configuration
│   ├── settings.py
│   ├── urls.py
│
├── mailapp/           # Main application
│   ├── models.py
│   ├── views.py
│   ├── templates/
│   ├── urls.py
│
├── .venv/             # Virtual environment (not pushed)
├── db.sqlite3         # Database file
├── manage.py
└── requirements.txt
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```
git clone https://github.com/your-username/dheemail.git
cd dheemail
```

---

### 2. Activate Virtual Environment

If `.venv` is outside the project:

```
..\.venv\Scripts\Activate.ps1
```

If `.venv` is inside the project:

```
.\.venv\Scripts\Activate.ps1
```

---

### 3. Install Dependencies

```
pip install -r requirements.txt
```

---

### 4. Apply Migrations

```
python manage.py makemigrations
python manage.py migrate
```

---

### 5. Create Admin User

```
python manage.py createsuperuser
```

---

### 6. Run the Server

```
python manage.py runserver
```

---

### 7. Open in Browser

```
http://127.0.0.1:8000/
```

---

## 🔑 Admin Panel

Access the admin dashboard:

```
http://127.0.0.1:8000/admin/
```

---

## 👤 Custom User Model

This project uses a custom user model instead of Django’s default `User` to allow:

* Better flexibility
* Easy future scaling
* Custom authentication logic

---

## 📬 Core Functionalities

* User Registration & Login
* Send messages between users
* View Inbox
* View Sent Messages

---

## 🚫 Files to Ignore (.gitignore)

```
.venv/
__pycache__/
db.sqlite3
*.pyc
.env
```

---

## 🌱 Future Enhancements

* 📱 Responsive UI (Bootstrap / Tailwind)
* 🔍 Search & Filters
* 📎 File Attachments
* 🌐 Deployment (Render / AWS / Railway)

---

## 🤝 Contribution

1. Fork the repository
2. Create a new branch
3. Make changes
4. Commit and push

```
git checkout -b feature-name
git commit -m "Added feature"
git push origin feature-name
```

---

## 📄 License

This project is for educational purposes.

---

## 🙌 Acknowledgements

* Django Documentation
* Open-source community

---
