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

## Screenshots
<img width="1882" height="894" alt="log in" src="https://github.com/user-attachments/assets/dcac9a24-2bc7-410e-890d-a973bfc227c9" />
<img width="1915" height="903" alt="dashboard" src="https://github.com/user-attachments/assets/e3f38057-69e5-4dd1-94a3-076aa156dfd3" />
<img width="1893" height="896" alt="compose" src="https://github.com/user-attachments/assets/95936d7b-e432-4378-8d32-993bc4e8a49d" />
<img width="1911" height="886" alt="drafts" src="https://github.com/user-attachments/assets/9ae4d87a-de5b-4ca1-9a16-0c7ef8dd481d" />
<img width="1897" height="858" alt="manageacc" src="https://github.com/user-attachments/assets/013576dd-ff4b-47e7-9424-d9e70f561920" />
<img width="1887" height="354" alt="2" src="https://github.com/user-attachments/assets/d096e147-e5b2-43d8-9270-b9c711463821" />



```


## 🙌 Acknowledgements

* Django Documentation
* Open-source community

---
